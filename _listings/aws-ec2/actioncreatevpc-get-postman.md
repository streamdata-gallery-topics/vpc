{
  "info": {
    "name": "AWS EC2 API Create Vpc",
    "_postman_id": "2e59a838-a2f0-4336-b76a-5afbff1462bd",
    "description": "Creates a VPC with the specified IPv4 CIDR block.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "8f5776f7-676d-4ee4-9ede-3fbbfdbfbdbd",
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
              "id": "3af0535a-c249-405d-b5b1-e2a1ca3dd8ad"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "24a82f47-ad39-4b7b-802d-4c4ded35d39b",
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
              "id": "06b8b677-87e6-4cda-8613-0de63f82775f"
            }
          ]
        },
        {
          "id": "f9d72bcb-7057-4855-8411-a5ab73b85646",
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
              "id": "7212b626-e609-4f49-b21a-e35c4a89e776"
            }
          ]
        },
        {
          "id": "8e1f7376-1aa6-4d67-a5e1-fa99c0e73378",
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
              "id": "03aa59b3-b4d3-4425-9afe-227a4b4776bd"
            }
          ]
        },
        {
          "id": "44f3e013-5038-4a5a-972e-12fdad4bb551",
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
              "id": "aaf94824-e69a-4907-9f41-b2e68550ba7e"
            }
          ]
        },
        {
          "id": "06156f9c-1fb8-48a8-9051-a5c131885640",
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
              "id": "a2671540-5447-4ec8-8004-1ef9295eb298"
            }
          ]
        },
        {
          "id": "5decb7fe-8357-4aee-9b97-ebb650fb8a05",
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
              "id": "f121bc70-9ab7-4694-a790-0f650bc1801f"
            }
          ]
        },
        {
          "id": "c7545004-083d-4045-b46f-8ebfd4df90ed",
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
              "id": "ee6f4b22-78c0-4613-8d97-4b283f963599"
            }
          ]
        },
        {
          "id": "06b5cc01-a700-478c-b48f-2df89039f04a",
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
              "id": "d5723f4c-a968-4394-a0ec-0b84ed9f44bc"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "070344c4-9a86-43ea-ba59-cb41a390fc7c",
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
              "id": "f5bcb1b2-8a4e-4e73-a941-202a18966acf"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "2f612aea-260d-49ea-a8e3-94456bb3e8a9",
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
              "id": "9ba721dd-4396-4e76-805a-e66b8af28c1f"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "97ed02db-4ef0-48a1-80ea-e68f92d29383",
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
              "id": "48de780c-1f6a-4cfb-8bbf-4fe5df4a8c30"
            }
          ]
        },
        {
          "id": "9d21ae40-5156-4a32-821e-a1b678994cab",
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
              "id": "fb0c0b80-88b4-4aee-8c3e-149880e90bea"
            }
          ]
        },
        {
          "id": "f24fccca-7522-4365-b563-e6edd2ee62fb",
          "name": "cancelconversiontask",
          "request": {
            "url": "http://example.com/api/?Action=CancelConversionTask",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels an active conversion task."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59ff8875-01ec-4876-b2f3-44ff119c7ac9"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "5ecbe788-be0b-41b7-bf57-be4aa29cc36d",
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
              "id": "38716a32-17f4-4d23-80bc-ab766f2be70e"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "2d6df823-e7bc-4b09-a5ca-be87a75ca3f4",
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
              "id": "27e6f276-6baa-4353-9ab6-bd2d57d4cd86"
            }
          ]
        },
        {
          "id": "6be67289-b360-416d-91c9-646d92a51975",
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
              "id": "3f46e26c-0875-4138-b844-9c45f08a6845"
            }
          ]
        },
        {
          "id": "ebdb7f3d-654c-49ca-b373-1dd58a2383e8",
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
              "id": "558b9a3a-d517-48c5-8568-2de4c34b0117"
            }
          ]
        },
        {
          "id": "005922bd-e9ce-4b91-819d-7c7da69e2dc2",
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
              "id": "389bfd69-375f-4b71-9dfe-0d3c58c98289"
            }
          ]
        },
        {
          "id": "89c6d365-7ec7-4eaa-a8ad-7c2126aa6298",
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
              "id": "5b51cac0-2a17-4c9b-bf8f-c63b269a7f7a"
            }
          ]
        },
        {
          "id": "dbe19a6c-be91-4cec-95d2-0bbfc32eba0d",
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
              "id": "6f10f935-0ede-481f-92dd-07a945f056ae"
            }
          ]
        },
        {
          "id": "e69e52b0-a10a-4342-9bd3-6233aee20142",
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
              "id": "ea521433-0ae5-4a87-b252-cb9f6f795d71"
            }
          ]
        },
        {
          "id": "03f0ef9f-97d8-459c-ac0e-a489b254aa57",
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
              "id": "5fd5d0df-d6d3-44cf-9e26-e6c618c9a57f"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "42573bbd-907b-40f3-bbf4-81d626faca1b",
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
              "id": "8c74c73e-6c6e-4ac9-b40d-5d0a05fefc6f"
            }
          ]
        },
        {
          "id": "c1f79ce4-b4e3-40c7-8caf-3d136e4eafc5",
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
              "id": "303d3502-7d0c-409a-bf8b-b1ae4f83fe31"
            }
          ]
        },
        {
          "id": "aea9199e-c98c-4828-ba6e-80b85e7e2f4a",
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
              "id": "38134f93-6df9-4110-8956-920785900486"
            }
          ]
        },
        {
          "id": "08d351e2-bb38-4e0d-821d-ce09664a628b",
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
              "id": "d221c358-4c97-4c8c-acce-0d37b200a1bf"
            }
          ]
        },
        {
          "id": "c126c5a2-70ea-44a4-96f2-e3f8465b83d5",
          "name": "createvpc",
          "request": {
            "url": "http://example.com/api/?Action=CreateVpc?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a VPC with the specified IPv4 CIDR block."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89079990-ac3f-46df-b1eb-eef4ba3cd272"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "e849fe5a-8311-4592-bbba-b1b4cad3cf2d",
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
              "id": "e4511f8d-cea3-4cca-81d8-3afb33d59561"
            }
          ]
        },
        {
          "id": "effe9dea-89f6-4ee1-99b1-780e260f39b7",
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
              "id": "45ca4b5b-d778-4884-9ad1-e6b6d13b6a23"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "d6acd31e-2f1b-453d-9239-726b16ae17cd",
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
              "id": "50240cd7-7b9e-4764-b97b-e97d2cd2ee20"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "700b44dc-a92b-45da-b527-9d5fffe3b758",
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
              "id": "d24c0958-9b05-46bf-907b-65b54de7bf83"
            }
          ]
        },
        {
          "id": "f8e4ba5e-10fe-4c01-be38-1d6a332e1945",
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
              "id": "d3b1f4d8-b286-421e-9d8b-991b9b5f81c4"
            }
          ]
        },
        {
          "id": "37b8ac7e-48e1-4ca0-b561-001df21d3a10",
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
              "id": "1b912a94-8cae-4cd8-8870-9e9ac1571ee2"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "162a7199-1d6e-4c5f-8f03-a4e5d69c5cc7",
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
              "id": "8947dc50-4260-4b9e-84d8-6536fa863999"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "8a31a7de-0bcc-4509-b0e8-c831d213a4c7",
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
              "id": "39257d59-6569-48f0-8e94-58a98ba6b041"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "22aa58d5-2dc4-4d8d-983b-e6d8a5427c67",
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
              "id": "dc1a1124-0fb8-456e-b221-feb40e86de8c"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "9eebcf6f-ee58-4538-b09b-b70abfd7d8fd",
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
              "id": "3b72225d-3a2a-405e-8280-3e025285d0e7"
            }
          ]
        },
        {
          "id": "96cc951d-dfa1-4542-8a85-ab999921f6e2",
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
              "id": "312f6825-cdac-4fb9-bfa6-8704f581bc53"
            }
          ]
        },
        {
          "id": "dc68088a-8b78-463a-ae59-903758537888",
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
              "id": "a8b2881f-52bb-465c-bd84-4a54eec5a7fd"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "91f770d9-37ec-43ad-ba1c-5322751a6f98",
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
              "id": "66658087-e89a-4932-be9d-43aa22dcb681"
            }
          ]
        },
        {
          "id": "fda03df3-1383-4018-84a3-b5c537e80db9",
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
              "id": "4d2be860-4e55-4157-9abb-1a88c5ba89b5"
            }
          ]
        },
        {
          "id": "e09e1af8-4204-4794-a20b-5ea5996cfed1",
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
              "id": "bf04d9c2-8199-4aac-8f90-ca6db31bdad5"
            }
          ]
        },
        {
          "id": "bddaccbd-c3b7-40bc-aed2-0c580f4a23e8",
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
              "id": "624418b6-1207-40ab-8bda-fbf1c680ecb2"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "ee09707b-74d2-40cf-89b5-c749a4ed77aa",
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
              "id": "e24c04a6-f8e2-4ae6-89e3-a1c62cda011d"
            }
          ]
        },
        {
          "id": "1f51faca-8a1e-4df5-8060-ef8ed08aa6a5",
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
              "id": "d4187d81-f14a-45b4-b6a9-833c2562aa44"
            }
          ]
        },
        {
          "id": "6f892f6f-c2fa-4169-829f-9b14df99fcc7",
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
              "id": "8f253008-75fd-498a-9149-e8b7b909d6e8"
            }
          ]
        },
        {
          "id": "b2cfc699-2127-48f7-bbc0-f1e1c6a252f4",
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
              "id": "d4c5f243-7975-4824-ac91-5766a779cec2"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "82c677ee-ff04-484d-96a5-89dcec4ca9c4",
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
              "id": "97239c83-3cb2-464e-b8e7-b4bfd7146b91"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "7ec9b5bd-f1a7-4177-b89c-ac9cc0458a72",
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
              "id": "1ce150c7-458f-4ad5-ba1f-3c434b280030"
            }
          ]
        },
        {
          "id": "33db6063-8d6d-4514-a3b5-ff4bf3b7c538",
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
              "id": "dac9c6a3-0e44-4541-8b3b-1c9f9dd69686"
            }
          ]
        },
        {
          "id": "7f19f567-4a71-4da2-b540-15445f0e8b7b",
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
              "id": "99bd7436-b840-4b33-9096-68d7422a13f7"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "709bca5a-dbe1-4aac-b8c2-afb3bd2eaddb",
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
              "id": "ae0a1b6b-871d-47e2-b8b6-9d16378bbf23"
            }
          ]
        },
        {
          "id": "45cc7d6a-65ae-42b6-a30d-dfba06bb8cee",
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
              "id": "ad15ec2a-d24f-424e-bccc-7a2cac701dae"
            }
          ]
        },
        {
          "id": "35bdeac7-2bc2-4358-8ade-ad61fd487796",
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
              "id": "31fb7647-75f8-4a97-a921-9768de9b40a2"
            }
          ]
        },
        {
          "id": "a3b35a97-983a-4e4c-a41b-5f94eadb4ce6",
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
              "id": "2cbbbbbf-1685-40a7-9e85-ab633c3feec8"
            }
          ]
        },
        {
          "id": "67953db8-857f-4b34-a934-f616f284e922",
          "name": "importsnapshot",
          "request": {
            "url": "http://example.com/api/?Action=ImportSnapshot?AvailabilityZone=AvailabilityZone&Description=Description&DryRun=DryRun&Image=Image&Volume=Volume",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your import snapshot tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36af0272-4455-4964-88f8-6b872a2a9764"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "1e9cf04b-676d-4a39-a324-cf89de8607e1",
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
              "id": "5f0d9564-a0dd-47fb-9d38-708391005d73"
            }
          ]
        },
        {
          "id": "1f427432-edb8-4264-b95a-2db5ed4fb1bb",
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
              "id": "3fc655b0-cdf6-4d5c-afa2-53b03b8e166b"
            }
          ]
        },
        {
          "id": "56e91dbb-2a18-4571-9707-22099242dd07",
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
              "id": "0c90976b-86a8-43a2-aec8-d98be0353184"
            }
          ]
        },
        {
          "id": "190fd7fa-4f78-4cd6-b593-803984b0d8ef",
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
              "id": "64c92187-82f8-4b96-8617-79e590517381"
            }
          ]
        },
        {
          "id": "cf1314d4-8e44-4fff-91c2-9265059c2e3a",
          "name": "importvolume",
          "request": {
            "url": "http://example.com/api/?Action=ImportVolume?ExportTaskId=ExportTaskId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an import volume task using metadata from the specified disk image."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "698c860e-6813-4821-9738-b2ae2f29fb9e"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "127dc9f0-502a-4434-a517-abe74bc2f4e7",
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
              "id": "38a21fea-b78a-4021-8cd0-892a90766c17"
            }
          ]
        },
        {
          "id": "464a449e-bde2-4f70-a3ba-7d3d4c0a2335",
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
              "id": "fafde9ff-84b6-44ae-8e81-b361ff1c36c9"
            }
          ]
        },
        {
          "id": "b1d839e1-39fb-45d8-bcd7-b06ec3784a01",
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
              "id": "6a83c91d-4c5b-4c87-8a11-b544a0448b44"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "64a690fd-2904-470f-a1ce-aedc165dbe02",
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
              "id": "4226325d-28af-4956-afaa-bb5e2ae2d897"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "69d14977-548f-4479-a22b-909a54170c7d",
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
              "id": "0dfefc26-a9c7-49b0-9561-1838018b18b4"
            }
          ]
        },
        {
          "id": "55fa7e4c-9cdc-40db-94e6-aa85b75340e8",
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
              "id": "0c13bba5-3f4e-4306-a41a-20b631677cec"
            }
          ]
        },
        {
          "id": "407f9728-453f-4d70-b08b-a5134ac11813",
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
              "id": "7cb628bb-6925-40c9-b68a-0f2a0d20d90e"
            }
          ]
        },
        {
          "id": "90bebb38-f9a5-417f-bf58-cc0758cf78d1",
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
              "id": "60a05c9c-920e-46d1-87fd-fb3c7f0dd397"
            }
          ]
        },
        {
          "id": "37ffce0d-ec88-433e-addd-c598ace23570",
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
              "id": "e106b197-525d-4ea0-b026-8d6a64ffae30"
            }
          ]
        },
        {
          "id": "42b80152-ce75-43d9-8064-5fc2a04ab74a",
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
              "id": "7133af94-7b2d-43a8-a520-053e97cdaef9"
            }
          ]
        },
        {
          "id": "c2b6383b-0b3b-42a1-a38b-8e5b412604aa",
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
              "id": "899d107b-d967-4e6e-888f-abfb492c608c"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "1fc10fa2-a371-4581-86a4-e32941e56d26",
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
              "id": "3efb438a-922a-455c-8f28-151ca6356c34"
            }
          ]
        },
        {
          "id": "e3fb268c-2ae4-4f12-bb7b-626f9c9f9028",
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
              "id": "270019c2-34a9-4f10-9229-46f0f1ed3f18"
            }
          ]
        },
        {
          "id": "45818b41-04ad-4c64-bc90-aee532af103e",
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
              "id": "93236004-c06d-4edd-8d86-827bb312b03c"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "b83453d2-6253-4d53-acd1-e4f6c3f51e13",
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
              "id": "f63f1a03-d648-4a6d-9232-650729369a4d"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "f6b3d34e-deeb-429c-8aed-e265a6c561e6",
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
              "id": "1ce8399a-0856-4444-b4a3-ada7792091b5"
            }
          ]
        },
        {
          "id": "4ac6e0e4-a9b3-4157-8c50-37161ec03ac5",
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
              "id": "01a3c776-f3eb-49e9-a28f-d9a51a4113ed"
            }
          ]
        },
        {
          "id": "3693e125-c2d5-411d-aef8-426e36bd7942",
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
              "id": "42612036-5142-48d4-84bd-34fafdb13a12"
            }
          ]
        },
        {
          "id": "1a3b62d9-0fbc-438e-8707-5be2f9968a01",
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
              "id": "e34fea7f-048b-43ee-a5c7-3971b27393ff"
            }
          ]
        },
        {
          "id": "ca135771-ded1-494b-a85d-d7a972bb404b",
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
              "id": "ee83c7a0-faca-4347-be09-7a1b413dbb8c"
            }
          ]
        },
        {
          "id": "a9d2830e-d441-4403-a74a-e7cfc16e940b",
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
              "id": "760580e5-3c13-4335-9f8f-2fe5759d8214"
            }
          ]
        },
        {
          "id": "4fe2965c-fd9a-49fe-b591-051e02666da5",
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
              "id": "33002bf9-54a9-4ef1-a58e-e672125b7e5f"
            }
          ]
        },
        {
          "id": "1e61d809-265a-4c47-b346-9032f8b93165",
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
              "id": "3cae97ce-d42a-439f-8b32-6a25ee7e1ee8"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "c516f077-9beb-421b-b0fa-89a97264a4cf",
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
   