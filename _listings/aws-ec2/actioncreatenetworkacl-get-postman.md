{
  "info": {
    "name": "AWS EC2 API Create Network Acl",
    "_postman_id": "d85db849-9cfd-4e82-986a-84c7b2af8c72",
    "description": "Creates a network ACL in a VPC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "003564a4-04d5-446d-9602-7d314114b7a4",
          "name": "describeaccountattributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAccountAttributes?ClientToken=ClientToken&Description=Description&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&Name=Name&SourceImageId=SourceImageId&SourceRegion=SourceRegion",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes attributes of your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ed9d1ffb-c245-4586-bbfe-ab00cbfadba9"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "03c81ed5-113a-4c44-8946-abfdc8781327",
          "name": "copyimage",
          "request": {
            "url": "http://example.com/api/?Action=CopyImage?BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&InstanceId=InstanceId&Name=Name&NoReboot=NoReboot",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the copy of an AMI from the specified source region to the current region."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c64e930a-a58a-4a8d-98df-3ff652a202b7"
            }
          ]
        },
        {
          "id": "4552cb19-9592-4c86-9b1a-5b0b4c6262d1",
          "name": "createimage",
          "request": {
            "url": "http://example.com/api/?Action=CreateImage?DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance that is either running or stopped."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c8b917f-87d7-4993-997a-ba4d08338341"
            }
          ]
        },
        {
          "id": "9d16e606-0ef4-4f68-9e64-d2ae740bdf52",
          "name": "deregisterimage",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "956655ae-07f1-4ee4-9e5f-161fb9206aab"
            }
          ]
        },
        {
          "id": "60dbe668-ed35-4211-8fb4-e5029635f805",
          "name": "describeimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImageAttribute?DryRun=DryRun&ExecutableBy.N=ExecutableBy.N&Filter.N=Filter.N&ImageId.N=ImageId.N&Owner.N=Owner.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d969d7e5-c6d0-469f-94d2-c0d003fd51c0"
            }
          ]
        },
        {
          "id": "5c980aab-32bc-4740-bc98-d24fc30dd0cb",
          "name": "describeimages",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImages?Attribute=Attribute&Description=Description&DryRun=DryRun&ImageId=ImageId&LaunchPermission=LaunchPermission&OperationType=OperationType&ProductCode.N=ProductCode.N&UserGroup.N=UserGroup.N&UserId.N=UserId.N&Value=Value",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the images (AMIs, AKIs, and ARIs) available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a1114c4-8818-49c0-99cc-80b2989f5f32"
            }
          ]
        },
        {
          "id": "61b25a58-44d7-4334-be0b-fa63d7d2e3a7",
          "name": "modifyimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyImageAttribute?Architecture=Architecture&BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&EnaSupport=EnaSupport&ImageLocation=ImageLocation&KernelId=KernelId&Name=Name&RamdiskId=RamdiskId&RootDeviceName=RootDeviceName&SriovNetSupport=SriovNetSupport&VirtualizationType=VirtualizationType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df0c1887-9fe3-4f09-9d5d-a3a50e4a587f"
            }
          ]
        },
        {
          "id": "4d4c2514-4770-401b-9932-3e83700d18b5",
          "name": "registerimage",
          "request": {
            "url": "http://example.com/api/?Action=RegisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers an AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3bfb217c-7a72-4a6b-a077-c1ea265f242e"
            }
          ]
        },
        {
          "id": "30447b17-d23a-4993-9f70-e10cbdd7c263",
          "name": "resetimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetImageAttribute?DryRun=DryRun&InstanceId=InstanceId&ProductCode=ProductCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets an attribute of an AMI to its default value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef1cea34-faea-4432-bbae-4bf5c06908e2"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "c8f393fa-fe0d-456a-8513-590017eeb399",
          "name": "confirmproductinstance",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmProductInstance?DryRun=DryRun&InstanceId=InstanceId&Storage=Storage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Determines whether a product code is associated with an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "587b2f05-4941-447d-853c-e6aa315f3479"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "a262a0bb-29fb-4042-bad8-41e75b4b3042",
          "name": "bundleinstance",
          "request": {
            "url": "http://example.com/api/?Action=BundleInstance?BundleId=BundleId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Bundles an Amazon instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de4db782-5ddb-4560-b7cf-1f4caa8da2fd"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "e30f749f-26db-455f-876c-fc3f8636cdb1",
          "name": "cancelbundletask",
          "request": {
            "url": "http://example.com/api/?Action=CancelBundleTask?BundleId.N=BundleId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels a bundling operation for an instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de2fa22b-1d1d-4e7b-8215-93f6bbca8433"
            }
          ]
        },
        {
          "id": "8afc341e-5102-43a0-a81c-4d054ef8ce80",
          "name": "describebundletasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeBundleTasks?DryRun=DryRun&InstanceId=InstanceId&SecurityGroupId.N=SecurityGroupId.N&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your bundling tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "342b03e6-622f-485d-8a52-22125fa996c2"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "1c71eb08-3219-4855-a246-21420841a9e1",
          "name": "attachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=AttachClassicLinkVpc?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Links an EC2-Classic instance to a ClassicLink-enabled VPC through one or more of the VPC's\n\t\t\tsecurity groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c97612bf-0ffe-4476-91ea-516eddb512d1"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "c1300c5d-4d54-42f4-a46b-ccf9f42fe66f",
          "name": "describeclassiclinkinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeClassicLinkInstances?DryRun=DryRun&Filter.N=Filter.N&VpcId.N=VpcId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your linked EC2-Classic instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf851391-1d55-4713-acb6-13bb93bd101e"
            }
          ]
        },
        {
          "id": "3cc459ae-c939-4402-aa7d-c95c1ef170e0",
          "name": "modifyinstanceplacement",
          "request": {
            "url": "http://example.com/api/?Action=ModifyInstancePlacement?ClientToken=ClientToken&CurrencyCode=CurrencyCode&HostIdSet.N=HostIdSet.N&LimitPrice=LimitPrice&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Set the instance affinity value for a specific stopped instance and modify the\n            instance tenancy setting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d7ca7e8-9299-4c87-aa54-ccc38d6bdac0"
            }
          ]
        },
        {
          "id": "16246df9-fecf-4667-af1a-49afaa470b47",
          "name": "describeinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceAttribute?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b066577-3df2-43e1-ba6a-89515993e1fa"
            }
          ]
        },
        {
          "id": "414385b8-cf69-4a10-a9af-cc0654a5265e",
          "name": "describeinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstances?DryRun=DryRun&Filter.N=Filter.N&IncludeAllInstances=IncludeAllInstances&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71ea9df2-3edc-474d-afd4-b0b407228710"
            }
          ]
        },
        {
          "id": "7c6e7f1f-e906-49e7-aca5-1ed73c0fb613",
          "name": "modifyinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyInstanceAttribute?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de7ffcca-a8bb-4c58-8c4a-5c02b22ceedf"
            }
          ]
        },
        {
          "id": "47e1ea07-dddc-46f5-9065-7662499495c4",
          "name": "reportinstancestatus",
          "request": {
            "url": "http://example.com/api/?Action=ReportInstanceStatus?Attribute=Attribute&DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Submits feedback about the status of an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74873910-e86c-40d6-8b8f-34a2e2ba0286"
            }
          ]
        },
        {
          "id": "3a9720bd-da51-4bf2-afd8-f0e597f6ba9f",
          "name": "resetinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetInstanceAttribute?AdditionalInfo=AdditionalInfo&BlockDeviceMapping.N=BlockDeviceMapping.N&ClientToken=ClientToken&DisableApiTermination=DisableApiTermination&DryRun=DryRun&EbsOptimized=EbsOptimized&IamInstanceProfile=IamInstanceProfile&ImageId=ImageId&InstanceInitiatedShutdownBehavior=InstanceInitiatedShutdownBehavior&InstanceType=InstanceType&Ipv6Address.N=Ipv6Address.N&Ipv6AddressCount=Ipv6AddressCount&KernelId=KernelId&KeyName=KeyName&MaxCount=MaxCount&MinCount=MinCount&Monitoring=Monitoring&NetworkInterface.N=NetworkInterface.N&Placement=Placement&PrivateIpAddress=PrivateIpAddress&RamdiskId=RamdiskId&SecurityGroup.N=SecurityGroup.N&SecurityGroupId.N=SecurityGroupId.N&SubnetId=SubnetId&UserData=UserData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets an attribute of an instance to its default value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1610044-a0f3-4bb4-80d9-a3e45a83e068"
            }
          ]
        },
        {
          "id": "7cc7e14a-2f8e-429b-8d25-e3e3ed079da0",
          "name": "unmonitorinstances",
          "request": {
            "url": "http://example.com/api/?Action=UnmonitorInstances?DryRun=DryRun&InternetGatewayId=InternetGatewayId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables detailed monitoring for a running instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "782398af-e9aa-4333-a144-7a740b01dad0"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "959214ee-321c-4c8c-8565-5bc86252a4cf",
          "name": "describevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLink?MaxResults=MaxResults&NextToken=NextToken&VpcIds.N=VpcIds.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1dab5557-330a-47ad-8a7b-c0c884f1ac42"
            }
          ]
        },
        {
          "id": "5eb1780e-06ab-4199-b10e-910146015290",
          "name": "detachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=DetachClassicLinkVpc?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks (detaches) a linked EC2-Classic instance from a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb795f73-fc03-4e4a-9ab2-8ee0c172d7d4"
            }
          ]
        },
        {
          "id": "f1f340a6-2bd7-4f37-81b2-446010f41ab4",
          "name": "disablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13477fd0-0b24-4234-a4e5-1e3a962f8706"
            }
          ]
        },
        {
          "id": "b5d564bf-1333-4df9-979b-3560b21be8d0",
          "name": "enablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "627b82e2-d4cb-49e7-93f0-a688119645e7"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "2fc65a41-abdc-4dbf-8b9e-b7f0bdd2bccb",
          "name": "describevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLinkDnsSupport?DryRun=DryRun&InstanceId=InstanceId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink DNS support status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad203fbb-0b9d-4d6b-bd2b-3c37bf5a03e2"
            }
          ]
        },
        {
          "id": "2ac899a5-0668-4473-82d9-fab1ba8d69e5",
          "name": "disablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLinkDnsSupport?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink DNS support for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9dbbde9-0a77-4587-88af-a312bf44c114"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "034a3d84-50e2-414e-b0b4-6776f2082920",
          "name": "enablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLinkDnsSupport?BgpAsn=BgpAsn&DryRun=DryRun&IpAddress=IpAddress&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC to support DNS hostname resolution for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2a0e9d8-f442-4fe8-823c-21ad70ab7dc2"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "0542b971-fbc4-4aee-87c3-c69459d3d069",
          "name": "createcustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateCustomerGateway?CustomerGatewayId=CustomerGatewayId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information to AWS about your VPN customer gateway device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8720a2a-2d49-4138-b997-e25b217998b2"
            }
          ]
        },
        {
          "id": "8c610ed2-fd18-4ead-b5d3-3438cf3d9388",
          "name": "createnatgateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateNatGateway?NatGatewayId=NatGatewayId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a NAT gateway in the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d82c3b5f-0d90-4a43-86b3-e9497fa0cafc"
            }
          ]
        },
        {
          "id": "14d600d4-e04f-4154-ae4c-23f8e8762536",
          "name": "deletenatgateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNatGateway?Filter.N=Filter.N&MaxResults=MaxResults&NatGatewayId.N=NatGatewayId.N&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified NAT gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d06be37-69dd-456e-be73-f7ea8bf17c89"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "6c54dec8-6f30-49fa-85be-11a7fcb389ff",
          "name": "deletecustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCustomerGateway?CustomerGatewayId.N=CustomerGatewayId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified customer gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d38ed24-7e23-4114-b194-9cbe5a459370"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "ec563870-556c-4b3d-896d-941e2c541b04",
          "name": "describecustomergateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCustomerGateways?AutoPlacement=AutoPlacement&AvailabilityZone=AvailabilityZone&ClientToken=ClientToken&InstanceType=InstanceType&Quantity=Quantity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your VPN customer gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "349afe77-572c-480d-933e-bc8180357b11"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "02f40000-9ca7-4232-9c72-f28ca4315e6c",
          "name": "allocatehosts",
          "request": {
            "url": "http://example.com/api/?Action=AllocateHosts?Filter.N=Filter.N&HostId.N=HostId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allocates a Dedicated Host to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbcf4598-c9e2-454c-85d3-403226f508d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "2ace4128-965f-4719-8b91-eeecb36e3971",
          "name": "describehosts",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHosts?Filter.N=Filter.N&MaxDuration=MaxDuration&MaxResults=MaxResults&MinDuration=MinDuration&NextToken=NextToken&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Dedicated Hosts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd33a731-546d-4f44-8b71-6818a4283d3c"
            }
          ]
        },
        {
          "id": "eca6bd33-8927-4fdd-ba32-b8744517b110",
          "name": "modifyhosts",
          "request": {
            "url": "http://example.com/api/?Action=ModifyHosts?Affinity=Affinity&HostId=HostId&InstanceId=InstanceId&Tenancy=Tenancy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modify the auto-placement setting of a Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd9dfcc0-bc2c-4835-8d5d-0b0194cb20e4"
            }
          ]
        },
        {
          "id": "6ec2ca31-6e00-4a39-ab2d-6e5399918327",
          "name": "releasehosts",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseHosts?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "When you no longer want to use an On-Demand Dedicated Host it can be released."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6362562-21c9-4d79-8b00-b97a52b9eb58"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "a04ec06f-fc63-47bb-b7ec-b2f65d328161",
          "name": "describehostreservationofferings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservationOfferings?Filter.N=Filter.N&HostReservationIdSet.N=HostReservationIdSet.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Dedicated Host Reservations that are available to purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15a9499d-bc8b-40af-b8ee-a0e6b1de0b0f"
            }
          ]
        },
        {
          "id": "fa3b8235-3298-4ea3-8d32-d58179676832",
          "name": "describehostreservations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservations?HostIdSet.N=HostIdSet.N&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Dedicated Host Reservations which are associated with Dedicated Hosts in\n            your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3eed3a89-cc38-458f-8dc9-4c2db2f9c557"
            }
          ]
        },
        {
          "id": "16b75dde-f45f-4520-821a-6df928f46a7b",
          "name": "gethostreservationpurchasepreview",
          "request": {
            "url": "http://example.com/api/?Action=GetHostReservationPurchasePreview?AutoPlacement=AutoPlacement&HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Preview a reservation purchase with configurations that match those of your\n            Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b3595bb-02de-4823-ae2d-887f53d35936"
            }
          ]
        },
        {
          "id": "d028a6bc-7e66-4438-aafb-58a502640227",
          "name": "purchasehostreservation",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseHostReservation?HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchase a reservation with configurations that match those of your Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2eeb8d90-99c5-41eb-9538-d24fdd9ba091"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "5dfc34f5-e00c-4eb6-a40e-df86ef279a62",
          "name": "associatedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=AssociateDhcpOptions?DhcpConfiguration.N=DhcpConfiguration.N&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a set of DHCP options (that you've previously created) with the specified VPC, or associates no DHCP options with the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c3b2eb2-9f5e-41ab-9bc3-5e9cd9b781a9"
            }
          ]
        },
        {
          "id": "d5669d59-ec3c-4e01-8cb1-9632d3461408",
          "name": "createdhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=CreateDhcpOptions?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a set of DHCP options for your VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af17338b-e87c-4c99-9f7f-5550dc9d189e"
            }
          ]
        },
        {
          "id": "0aca3e28-bf30-4c03-ba1a-405026d4e415",
          "name": "deletedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDhcpOptions?DhcpOptionsId.N=DhcpOptionsId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified set of DHCP options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff80026b-94a3-46c1-964c-b674233a6c8a"
            }
          ]
        },
        {
          "id": "5e8e335b-7037-4992-847d-64e5bb5a80e7",
          "name": "describedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDhcpOptions?Device=Device&DryRun=DryRun&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your DHCP options sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2dbca1c0-141b-479b-a820-d4f2fbbdebeb"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "e5fdc3be-2a05-4e90-b7b5-61f495916b12",
          "name": "attachvolume",
          "request": {
            "url": "http://example.com/api/?Action=AttachVolume?Description=Description&DestinationRegion=DestinationRegion&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&PresignedUrl=PresignedUrl&SourceRegion=SourceRegion&SourceSnapshotId=SourceSnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an EBS volume to a running or stopped instance and exposes it to the instance with\n      the specified device name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "909b60ae-29e2-4717-b386-3aea06fbaf12"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "1a56689b-bce5-4f51-b3b5-d257dd2d35d2",
          "name": "copysnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CopySnapshot?Description=Description&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Copies a point-in-time snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b122a1c-0827-47fa-9cb6-ec6be50a5766"
            }
          ]
        },
        {
          "id": "24280fd8-7829-40f8-8f7e-8e74561ce34a",
          "name": "describesnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshotAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&Owner.N=Owner.N&RestorableBy.N=RestorableBy.N&SnapshotId.N=SnapshotId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "703c8c26-b025-4fe9-94be-21954c3d9b46"
            }
          ]
        },
        {
          "id": "40ec4d7a-df76-483c-b851-0cf5b3e05c2c",
          "name": "describesnapshots",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshots?Attribute=Attribute&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the EBS snapshots available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59fc016b-e2b5-41bd-8db5-aeb7c523f129"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "a3f69661-7123-4a90-97fe-7256394ae51a",
          "name": "createsnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshot?AvailabilityZone=AvailabilityZone&DryRun=DryRun&Encrypted=Encrypted&Iops=Iops&KmsKeyId=KmsKeyId&Size=Size&SnapshotId=SnapshotId&VolumeType=VolumeType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dae234db-9da1-43d8-ad17-e9ae3b66b8ba"
            }
          ]
        },
        {
          "id": "7d410093-e687-4531-a569-cc890d8d365e",
          "name": "deletesnapshot",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSnapshot?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "934226fb-0398-4c18-a152-d24abb17883c"
            }
          ]
        },
        {
          "id": "f094d446-d9bf-4c71-ae2f-b98186815ba2",
          "name": "modifysnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifySnapshotAttribute?AutoEnableIO=AutoEnableIO&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or removes permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89bf20db-a721-44f6-a623-f463ad44215a"
            }
          ]
        },
        {
          "id": "effc3a3a-d5f7-49fb-979b-0b88567ebe3a",
          "name": "resetsnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetSnapshotAttribute?Domain=Domain&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3027beec-1d8d-4e71-a18e-ebafb9971c90"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "e2c46384-0539-4c33-a0c4-5ec346378d26",
          "name": "createvolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateVolume?DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an EBS volume that can be attached to an instance in the same Availability Zone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0161e580-1a36-4212-ab1e-f187ee753f9e"
            }
          ]
        },
        {
          "id": "3362e6c6-d604-4c8e-ac90-44cb93f2ead4",
          "name": "deletevolume",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVolume?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified EBS volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94138acf-d49f-4ba0-ac74-f6f5989a0358"
            }
          ]
        },
        {
          "id": "606408c5-0e40-45cc-948d-161fe9ba2afb",
          "name": "detachvolume",
          "request": {
            "url": "http://example.com/api/?Action=DetachVolume?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches an EBS volume from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e506cc5-fe24-46b8-906e-2752c211b2ba"
            }
          ]
        },
        {
          "id": "21d294e7-45c5-4ea8-ae81-cf236f11f42c",
          "name": "modifyvolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyVolumeAttribute?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies a volume attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e5fea62-5103-4cad-acd0-b830762eacda"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "4cd63ae0-e963-4669-9b0d-e7a58067a1c1",
          "name": "describevolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d311c47b-e441-4349-a452-ebc5ddbd7bf7"
            }
          ]
        },
        {
          "id": "696110fd-05c5-4f7b-96e1-b8864e1e8e18",
          "name": "describevolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumes?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified EBS volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee58c7de-f251-4d59-8a31-aefaa45b3649"
            }
          ]
        },
        {
          "id": "35a6ce00-ac71-4f70-85d9-dbec30dc79df",
          "name": "enablevolumeio",
          "request": {
            "url": "http://example.com/api/?Action=EnableVolumeIO?Attribute=Attribute&CreateVolumePermission=CreateVolumePermission&DryRun=DryRun&OperationType=OperationType&SnapshotId=SnapshotId&UserGroup.N=UserGroup.N&UserId.N=UserId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables I/O operations for a volume that had I/O operations disabled because the data on the\n      volume was potentially inconsistent."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ceb1ebe6-34a9-432b-90b6-6ad3a26333b1"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "1603bebd-f66a-418a-8036-c74c64f01627",
          "name": "describevolumestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeStatus?Device=Device&DryRun=DryRun&Force=Force&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of the specified volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e45ba1f-f44e-4f22-acba-2247ae76b56c"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "c0d8abec-c67b-43f8-b7ea-8458e654f77b",
          "name": "allocateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AllocateAddress?AllocationId=AllocationId&AllowReassociation=AllowReassociation&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress=PrivateIpAddress&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Acquires an Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90d0e614-abb6-42a8-bf74-5df33f0c3782"
            }
          ]
        },
        {
          "id": "5391916f-d01d-4707-89f4-5465d0bc0f9a",
          "name": "associateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AssociateAddress?AllocationId.N=AllocationId.N&DryRun=DryRun&Filter.N=Filter.N&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates an Elastic IP address with an instance or a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c1cb1ea-5dc6-4d5e-9c6e-d92e5af9a7ee"
            }
          ]
        },
        {
          "id": "2f30d163-e6a1-4679-911c-89356fad8149",
          "name": "describemovingaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMovingAddresses?AssociationId=AssociationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your Elastic IP addresses that are being moved to the EC2-VPC platform, or that are being restored to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56833790-2ede-4334-859a-f079d3147ebf"
            }
          ]
        },
        {
          "id": "2ee16c08-94bc-4c06-b0b5-db4889929b6b",
          "name": "moveaddresstovpc",
          "request": {
            "url": "http://example.com/api/?Action=MoveAddressToVpc?AllocationId=AllocationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7275cdba-098c-4188-a65e-c2cd0e3cb959"
            }
          ]
        },
        {
          "id": "caab3dbb-ae89-4153-8434-a5071c2a99f4",
          "name": "releaseaddress",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Releases the specified Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a350829-4329-4f9c-9a36-cae248ac7de3"
            }
          ]
        },
        {
          "id": "d94f17b3-518b-4dc7-a444-38130026acf7",
          "name": "assignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignIpv6Addresses?AllowReassignment=AllowReassignment&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more IPv6 addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b762e3d-14f7-4ae9-ac35-6f3ebce02e44"
            }
          ]
        },
        {
          "id": "22e8eef3-b47f-4221-8302-1b66016da23b",
          "name": "assignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignPrivateIpAddresses?DeviceIndex=DeviceIndex&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more secondary private IP addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "489a4af9-d769-403e-ac9a-dc0f14b8e249"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "d9aaf54d-4dca-450c-9f39-801b99bb2250",
          "name": "describeaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAddresses?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Elastic IP addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "438f02f5-7c0e-444b-aff1-f245ca50dbcd"
            }
          ]
        },
        {
          "id": "ecce86dd-e4c7-4fd1-9a21-07d1c2310996",
          "name": "restoreaddresstoclassic",
          "request": {
            "url": "http://example.com/api/?Action=RestoreAddressToClassic?Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Restores an Elastic IP address that was previously moved to the EC2-VPC platform back to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eed8096d-67e6-4d1f-9d09-99150d5f5339"
            }
          ]
        },
        {
          "id": "a9e3f137-c377-4fee-8797-b0c4eddf289e",
          "name": "unassignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignPrivateIpAddresses?Attribute=Attribute&DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more secondary private IP addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0dbe961a-04b0-49d4-96ea-3659f61d2c08"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "d32e2c78-1ac2-4ed9-a765-8f8dc3e40f0f",
          "name": "disassociateaddress",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates an Elastic IP address from the instance or network interface it's associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "274cc5d2-dd14-4cc4-a49e-8079cf392e8c"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "ef7aaad1-4a10-46b1-9bae-3c1e269a60cd",
          "name": "attachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=AttachNetworkInterface?Description=Description&DryRun=DryRun&Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&PrivateIpAddress=PrivateIpAddress&PrivateIpAddresses.N=PrivateIpAddresses.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount&SecurityGroupId.N=SecurityGroupId.N&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches a network interface to an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af50b0e1-1709-40b3-8963-ea01bb2f12eb"
            }
          ]
        },
        {
          "id": "21ab92bb-176a-4d9e-994d-c49acb304620",
          "name": "createnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkInterface?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a network interface in the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c64bcc2-af7e-4bae-bd76-f4436e828ee1"
            }
          ]
        },
        {
          "id": "d15af71f-7763-4e34-ac99-061fe113e2ab",
          "name": "deletenetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkInterface?Attribute=Attribute&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfe18839-6a57-4d6a-891a-ef913f0ebee4"
            }
          ]
        },
        {
          "id": "6026491b-6ac4-4f5c-9a64-d2815d900260",
          "name": "describenetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaceAttribute?DryRun=DryRun&Filter.N=Filter.N&NetworkInterfaceId.N=NetworkInterfaceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d55410d-fe1b-4624-aab5-5cbb6202860b"
            }
          ]
        },
        {
          "id": "37513b7e-4187-4829-b058-474f7bc7c504",
          "name": "describenetworkinterfaces",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaces?AttachmentId=AttachmentId&DryRun=DryRun&Force=Force",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your network interfaces."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11996768-1fe7-45b4-987f-55f0a73494ed"
            }
          ]
        },
        {
          "id": "5dbb6eeb-c410-42af-bb65-c69c61b59735",
          "name": "detachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DetachNetworkInterface?Attachment=Attachment&Description=Description&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SecurityGroupId.N=SecurityGroupId.N&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches a network interface from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b53c4329-f4a1-4f4e-a789-b3e75d484c35"
            }
          ]
        },
        {
          "id": "e50689bc-b110-42b6-ba45-0b75fa68e56e",
          "name": "modifynetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyNetworkInterfaceAttribute?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29587a22-441a-44cd-b111-5fd53058f210"
            }
          ]
        },
        {
          "id": "9260d3b4-ea96-42a5-9c93-adb5ddd4c0c1",
          "name": "resetnetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetNetworkInterfaceAttribute?Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "322a49a7-e49e-45f0-af91-70394a840548"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "e021843d-791b-41b8-aa57-9f90a0e82c40",
          "name": "unassignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignIpv6Addresses?NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more IPv6 addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78b313c1-c047-4d50-b77f-40177376e05c"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "dde07ea0-2a6e-4fc7-97fb-b9891a2cc11d",
          "name": "describeinstancestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceStatus?DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1cca4e28-a26c-4311-b675-2921f239f450"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "99b5e6a3-37e0-444a-b6d5-9c4410e9c6b7",
          "name": "getconsoleoutput",
          "request": {
            "url": "http://example.com/api/?Action=GetConsoleOutput?DryRun=DryRun&InstanceId=InstanceId&WakeUp=WakeUp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the console output for the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "510db859-8b09-4e20-9a2f-ca296ce36ee6"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Screenshot",
      "item": [
        {
          "id": "d05e833a-789e-4dd4-a15f-c87c542298a2",
          "name": "getconsolescreenshot",
          "request": {
            "url": "http://example.com/api/?Action=GetConsoleScreenshot?DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a JPG-format screenshot of a running instance to help with troubleshooting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ca2e4ca-425e-446d-bf6c-fe00c4afa2af"
            }
          ]
        }
      ]
    },
    {
      "name": "Password Data",
      "item": [
        {
          "id": "6922d520-6400-499b-9e03-930287aa9376",
          "name": "getpasswordd