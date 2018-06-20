{
  "info": {
    "name": "AWS EC2 API Delete Vpc",
    "_postman_id": "bd38373b-e5ed-4040-affe-e05e658708ba",
    "description": "Deletes the specified VPC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "f781f4ff-c58f-4841-bff8-d6830187b4f3",
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
              "id": "ee043866-46b9-47ef-aae6-7f7c06c35b39"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "19671ed8-7840-49a9-a305-1146de3c27ac",
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
              "id": "4d2b60ea-3d87-4121-a005-fbbeea64d255"
            }
          ]
        },
        {
          "id": "5230c0e2-92a0-4c47-babd-07e0ba0bcaaa",
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
              "id": "1d0a459b-be3e-4fa7-8506-fde1ef2bdaec"
            }
          ]
        },
        {
          "id": "fc730a35-f926-4513-9ab9-ad42ede3ffd7",
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
              "id": "471f9e60-b8b7-4467-b635-888de4e0e6cc"
            }
          ]
        },
        {
          "id": "43360d0d-7deb-4590-b9ba-a5568cbcf743",
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
              "id": "ceeb6ed4-7cde-4f47-a0b6-ace731f64c4b"
            }
          ]
        },
        {
          "id": "4dc7ff67-472e-4de2-86cb-77d280abf225",
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
              "id": "f16f2f0f-d4f1-426e-93c1-c9f39a7a7eeb"
            }
          ]
        },
        {
          "id": "e69c7921-fb2a-4ea5-980d-3ad74a4db93d",
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
              "id": "5f9207b3-2b95-460e-9f7e-ee243e380479"
            }
          ]
        },
        {
          "id": "f254aea6-e8df-4135-96b7-be2f694bc6d2",
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
              "id": "824f639f-da51-46dc-85ba-dc0185be8397"
            }
          ]
        },
        {
          "id": "d11d4adf-e8ad-465a-94bc-f97ce6a933c2",
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
              "id": "c079e7b0-44b5-4874-99ef-a30f447cb765"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "94fecd05-0269-477e-a9a1-042c82641e9f",
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
              "id": "6893c2d1-1d49-4ae1-b6cb-a60367993230"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "f94d68d7-a7b3-4f9a-a542-efde5c682d61",
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
              "id": "76c35fe9-44c7-4027-aefd-b0aa69523ddb"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "0ba195d2-dfed-4e7f-8d96-836d8e5a4cba",
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
              "id": "1c89e678-c0bc-442a-b3f9-7aa580c840f4"
            }
          ]
        },
        {
          "id": "d5d22ecb-e080-4648-a218-dd74b631b2d2",
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
              "id": "3075e084-b3c6-49b2-9343-c46f381cdeee"
            }
          ]
        },
        {
          "id": "a5c4ced3-8473-4c54-9ce2-02219c9b3ba2",
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
              "id": "ec8950f7-df1d-438c-b05f-fcccb0eb7391"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "32f1f63a-ebe1-4db1-9fbe-0c01ae4f7d08",
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
              "id": "26bd0be6-3094-46a2-b050-bcc91f61d5c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "aef46744-549a-49fa-a894-41c699aa26d5",
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
              "id": "4aa01153-3c33-45dd-96cb-057424eec320"
            }
          ]
        },
        {
          "id": "87431896-a7a6-440c-a7b8-d9bbd44491bf",
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
              "id": "e0ea919f-1712-4103-b9ad-97211fa08d57"
            }
          ]
        },
        {
          "id": "217000a4-e2e2-4091-8d09-e6a61a75f466",
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
              "id": "02e4f690-e773-40c5-959a-e839e5e112d0"
            }
          ]
        },
        {
          "id": "5eb6f93e-7e9f-412e-9dc7-05041d28fc35",
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
              "id": "8f4a1468-4d81-405d-9379-729a2d68b81f"
            }
          ]
        },
        {
          "id": "9f1714c9-cb19-4c47-a9aa-4c2b35683ddc",
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
              "id": "c08f5541-8212-4fb6-8f86-f36aea7adbff"
            }
          ]
        },
        {
          "id": "91ae73bd-0411-4ae5-aeaf-12e2eeab3ea2",
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
              "id": "093671af-9b16-492e-ad84-6c731c025a4d"
            }
          ]
        },
        {
          "id": "fc8e7854-f88f-419c-a8cf-a35b7dc916da",
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
              "id": "6189f64d-b170-4d6b-bde5-9fa5996a7db6"
            }
          ]
        },
        {
          "id": "ca0b29eb-607f-4845-ab83-2543a149ca3c",
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
              "id": "b1900100-118e-4056-9d9c-808917df2ee7"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "03c9f000-26a6-4ca1-8331-3715e2a24057",
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
              "id": "297918eb-0b70-4680-96b9-88dcd6154f26"
            }
          ]
        },
        {
          "id": "3c24cba9-3cc2-44ca-bbba-c929a3543763",
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
              "id": "0710eb60-4680-4eb4-ba3b-0d1a48b5fd56"
            }
          ]
        },
        {
          "id": "af1c4fdc-9400-45bd-9a88-6063194c63a2",
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
              "id": "287c4e83-34bb-41be-b4af-c5c122fa221a"
            }
          ]
        },
        {
          "id": "660bfe6d-a8d4-4d72-ba65-3da23edf45ce",
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
              "id": "e55ac83e-fe12-4a0b-8a67-8a768e36e32b"
            }
          ]
        },
        {
          "id": "f6aa6935-225d-41bc-bb9f-fb7fc26d5d79",
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
              "id": "afee8903-8584-4678-9e40-8198b7650f58"
            }
          ]
        },
        {
          "id": "a5192064-499a-4465-a291-99bb491f475c",
          "name": "deletevpc",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVpc?Attribute=Attribute&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "552874a8-d742-40ea-ab5f-ed5e17e57b34"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "27a34549-78f7-4f1b-8533-8bbde3445c5a",
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
              "id": "571d58af-dbf6-4005-a7e3-4fb05bbf4cf5"
            }
          ]
        },
        {
          "id": "a75029c8-07e6-4041-8141-582a0528dedb",
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
              "id": "748faea5-850c-4800-8783-aba9c310fea9"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "5c03df46-5c61-4676-9e30-f173a3c0e824",
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
              "id": "0050bfc8-9f35-4a5a-99ff-02915a0631bd"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "4fff10e0-e03b-4d85-b904-1c89636a7f7e",
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
              "id": "243fae98-3da8-4caf-b502-23124be334b0"
            }
          ]
        },
        {
          "id": "84740817-2edf-47d2-b6be-48ff1d33126c",
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
              "id": "e3fdcca7-35af-488e-afdd-8c5048708514"
            }
          ]
        },
        {
          "id": "30c9580a-b37d-4753-bb01-b2b18954c8b9",
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
              "id": "340cb8f7-f1af-4ddf-8c06-84a4d8605637"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "5fdcf1c5-a18f-4c32-b201-0719284da9ce",
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
              "id": "b558fdb1-5b5d-4428-b3b4-222c7efc5820"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "c5cbcae3-21e1-4133-8d31-71b7e0f08546",
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
              "id": "3303675e-c188-4188-8745-f98e4a373c12"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "f15ec20a-0679-4453-b458-cd55b5e1ba42",
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
              "id": "f0af4f4c-742b-4bc4-9b30-856e6d76164a"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "1dbca431-07d9-48dc-83ad-13a7d1fde0cd",
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
              "id": "0330ca5b-eeed-4db9-97f0-2450e5afef80"
            }
          ]
        },
        {
          "id": "8ca2e843-ad90-490f-9dd3-f9c203ec465a",
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
              "id": "e6c6f004-dcf2-4f92-aac7-c7a3e29e9a1b"
            }
          ]
        },
        {
          "id": "b3bfe4e1-1ac6-49d5-86e0-3eac19fa85a5",
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
              "id": "2cf84c6c-f7b1-4d49-822e-679ba00636c7"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "62a56f70-6800-46c8-bc97-cb5a57b1c698",
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
              "id": "4141c07c-a938-4453-857e-475ad0ad3400"
            }
          ]
        },
        {
          "id": "32eb9723-e507-4009-b8ac-1ff537f92e90",
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
              "id": "0f6744b0-3a2c-4d14-8ac2-b40d33000440"
            }
          ]
        },
        {
          "id": "b9307917-2ee8-42f1-8be5-4e0d6151b107",
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
              "id": "638e838b-8dc8-4af9-9f89-0f18e38043c2"
            }
          ]
        },
        {
          "id": "69d9d411-93aa-44fa-9422-265b74b8138b",
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
              "id": "159eae4a-8a37-415b-81ac-e313796d8047"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "4136217d-d8f1-4c18-a86b-c2a1b97fc8aa",
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
              "id": "368a5876-92bd-4e58-bdee-01e787ac3528"
            }
          ]
        },
        {
          "id": "c9bd7d42-3ad1-48e1-8a4d-338bdf05f383",
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
              "id": "c84429d4-4ea4-4361-90c9-a83c73de4528"
            }
          ]
        },
        {
          "id": "81fec2da-801c-45fd-9b36-1c804827dd55",
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
              "id": "d925ba04-909e-4c25-aced-043bed053698"
            }
          ]
        },
        {
          "id": "f054429a-58d7-4efd-b280-75108fe3ee98",
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
              "id": "1e067181-7907-4212-86a6-b7e9ac7a7429"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "81254711-2c0f-4332-a62d-396cd3e2c7cf",
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
              "id": "7ad327df-70c3-42b8-bd3e-ce299217b9d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "7f536877-5e53-40ee-8b46-794b907651fc",
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
              "id": "d0f6a6c1-0859-422f-80c3-d8cb2230c4a4"
            }
          ]
        },
        {
          "id": "aee29f9f-872e-4a6e-ab3c-c3fedfa0eca7",
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
              "id": "41cdc5e0-02c1-4bff-a1e6-6fb5728c0b49"
            }
          ]
        },
        {
          "id": "e295602b-2685-4e33-9733-176719e02d4f",
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
              "id": "9ae34752-c06e-4eed-b7b9-c947b399eb04"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "4cf64625-68aa-4648-a1b2-cb72c4338b57",
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
              "id": "ac1a9beb-6b90-4c34-ab3c-563e58b45e19"
            }
          ]
        },
        {
          "id": "13d1a1b4-105b-474e-adff-a9306271e46e",
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
              "id": "8fb75c39-d989-4305-9483-1d987f61a7d4"
            }
          ]
        },
        {
          "id": "f30493b2-2c26-485b-becb-1507674c987c",
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
              "id": "92217736-ac32-47d2-95d6-f3fd9222b871"
            }
          ]
        },
        {
          "id": "db76a6d2-483e-4da8-96c6-88a37b8d0ab8",
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
              "id": "1a3987a4-8635-4c68-b2f0-7a3a135a9ae7"
            }
          ]
        },
        {
          "id": "b865078d-88ed-4e49-9484-635c111efa4c",
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
              "id": "387f778a-19b9-44ea-9450-7d9d580f98b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "fa98e77d-5bdd-4f2c-ab64-781d8977ba33",
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
              "id": "337a84c8-fa6b-410e-9f2b-eb384ac30594"
            }
          ]
        },
        {
          "id": "31a7fc7c-0c59-4fe0-a431-7e6bfc12dc12",
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
              "id": "9117aabe-a386-4f30-8023-de1bc27a1bab"
            }
          ]
        },
        {
          "id": "37fb4a1d-1b3d-49d0-a734-5f931541e5d7",
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
              "id": "a51b5ea1-47ae-43a8-9ce1-3dd862ad8de6"
            }
          ]
        },
        {
          "id": "5425317d-efcc-4185-ae33-841f39f23440",
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
              "id": "61615944-88e6-436d-9f5e-22bc466c3a22"
            }
          ]
        },
        {
          "id": "b56ba129-c11a-4b58-9198-3f788595a2d8",
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
              "id": "6fef4383-cbb9-4357-990f-f5f412d18c2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "f666e8ea-68c0-4268-b462-19627093c0de",
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
              "id": "cce7cd24-0f63-4f99-99eb-d0dae49d30f7"
            }
          ]
        },
        {
          "id": "4a19414e-3597-4b9a-92a1-2f2ff965b1c4",
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
              "id": "05704e1a-61e7-4538-a8e5-ce8a53be3c12"
            }
          ]
        },
        {
          "id": "d622eb05-5952-499f-8dec-0516dbf8feae",
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
              "id": "a9bfb1d9-8ec9-4b80-a07f-b9e4a2e05735"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "7d5109c1-cd65-4b40-923b-c4829b36d0d8",
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
              "id": "85b26b5e-a235-4417-af0d-d01e1d21555e"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "4e1b3904-7853-4c88-8f13-a49fea101102",
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
              "id": "43d8697d-d48e-4abe-abf7-5443add0d37a"
            }
          ]
        },
        {
          "id": "51d235b7-d7b7-48ca-8153-b3e1b2fb28d7",
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
              "id": "67c649c7-4627-4577-bd24-73ea3b755874"
            }
          ]
        },
        {
          "id": "ebdfdb12-4b8f-4a7c-b8cc-249ebb86552c",
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
              "id": "8824f7d1-ef5a-4264-9556-61153d7d15d0"
            }
          ]
        },
        {
          "id": "7635375c-14a4-42a0-a17f-66864cc3f02b",
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
              "id": "9e1757b5-48e9-43b2-9dd2-dd1819daca3b"
            }
          ]
        },
        {
          "id": "2e40276a-3787-446f-8a82-adb103ed0579",
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
              "id": "4384672a-db6e-4cac-ab59-e933322f0385"
            }
          ]
        },
        {
          "id": "c0704511-321a-4dfc-ae52-dafab0c7535c",
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
              "id": "2b0d3d13-dbf7-41ca-a212-ea8e331e5480"
            }
          ]
        },
        {
          "id": "68ac626a-99d8-4c8c-95a0-14b00efb9f84",
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
              "id": "67884652-b7ca-4774-8507-6ae29bdf9426"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "9ea7167f-c9c3-407b-9a81-c3b26e06a2be",
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
              "id": "e0863c86-44b5-44b9-ac8e-3ceb5ba6a3f6"
            }
          ]
        },
        {
          "id": "6c267770-7327-42b7-a9cc-6e09203c1494",
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
              "id": "b9e1eb85-3df8-4e24-b8f9-97d586cfa885"
            }
          ]
        },
        {
          "id": "bb90c501-786b-41ca-8fd0-5c641543905a",
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
              "id": "de5cdeee-468e-4c51-9524-83c516e81bf1"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "efaf6f8f-31a9-4e08-b8bf-b6a38ba0a3f4",
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
              "id": "65ba0c5e-530c-48d1-8114-58e85f24d41c"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "a915a243-515b-4211-8b84-7a57ded6e1f8",
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
              "id": "b9f87547-1b77-4df2-92b1-10ec4a0c898f"
            }
          ]
        },
        {
          "id": "bc47bc5c-a2e7-4959-b18a-8468f620e93d",
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
              "id": "d364f0c4-1964-43a3-b7ca-b0a6da5c4f9f"
            }
          ]
        },
        {
          "id": "865e35fb-3ea8-4332-92d9-f99733a0628c",
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
              "id": "c089a7cc-68cb-443e-b00b-4b7f26285b83"
            }
          ]
        },
        {
          "id": "088941de-6624-4c11-837b-cd4da8827438",
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
              "id": "e77044b0-2d5b-415b-838c-c44d8296797d"
            }
          ]
        },
        {
          "id": "bcad49ae-2b2a-4328-abe1-892e96908448",
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
              "id": "b9a03c51-b272-41cf-a6de-e9b23575277e"
            }
          ]
        },
        {
          "id": "3c5c5104-1d07-4f7f-aeca-d2e256de37aa",
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
              "id": "ef523148-fdab-4f7e-a0b3-6062e574f14a"
            }
          ]
        },
        {
          "id": "58690d49-96fe-41ba-b6b5-fe3f333fbb76",
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
              "id": "5fe1e57c-ba4a-47ff-bfca-181448230f6d"
            }
          ]
        },
        {
          "id": "2c756395-1e91-41b3-9789-6b70eefb07b8",
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
              "id": "df070207-7983-49c8-8733-5dcb72627013"
            }
          ]
   