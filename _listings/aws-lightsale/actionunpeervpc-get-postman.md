{
  "info": {
    "name": "Amazon Lightsale API Unpeer Vpc",
    "_postman_id": "ab5d087c-ff86-4859-a88a-a9d4dd9b0b18",
    "description": "Attempts to unpeer the Lightsail VPC from the user's default VPC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "901055af-9f48-47db-b99a-bf6d5c9570e2",
          "name": "allocateStaticIp",
          "request": {
            "url": "http://example.com/api/?Action=AllocateStaticIp?staticIpName=staticIpName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allocates a static IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d13045f8-272d-49a2-9226-dfed573f170b"
            }
          ]
        },
        {
          "id": "61d4df66-b456-4287-a852-af1de8885926",
          "name": "attachStaticIp",
          "request": {
            "url": "http://example.com/api/?Action=AttachStaticIp?instanceName=instanceName&staticIpName=staticIpName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches a static IP address to a specific Amazon Lightsail instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2db7e364-223d-42bf-8931-d37dc41d061d"
            }
          ]
        },
        {
          "id": "132ba02a-a000-4d63-a3ac-0d0209716323",
          "name": "detachStaticIp",
          "request": {
            "url": "http://example.com/api/?Action=DetachStaticIp?staticIpName=staticIpName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches a static IP from the Amazon Lightsail instance to which it is\n      attached."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "effce4c2-468f-4300-9c73-9522c9ee90ad"
            }
          ]
        },
        {
          "id": "a9e2afc2-9cef-4f01-bb94-1ee787f206ae",
          "name": "getStaticIp",
          "request": {
            "url": "http://example.com/api/?Action=GetStaticIp?staticIpName=staticIpName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a specific static IP."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23d3a703-7939-4fe9-80b8-52f8bf2e712c"
            }
          ]
        },
        {
          "id": "d4b11948-e014-46ca-8eda-24259d0a5ed9",
          "name": "getStaticIps",
          "request": {
            "url": "http://example.com/api/?Action=GetStaticIps?pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about all static IPs in the user's account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ac9b7e5-e291-43a9-9176-b4fcfcab81e2"
            }
          ]
        },
        {
          "id": "3e5fe5ef-c78a-41e9-ae5f-f0ac56161a2c",
          "name": "releaseStaticIp",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseStaticIp?staticIpName=staticIpName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specific static IP from your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a7128f8-fcb9-48eb-9822-100bea219b18"
            }
          ]
        }
      ]
    },
    {
      "name": "Instances",
      "item": [
        {
          "id": "c0385cf4-46e0-42ba-8eb5-c507faac00d5",
          "name": "closeInstancePublicPorts",
          "request": {
            "url": "http://example.com/api/?Action=CloseInstancePublicPorts?instanceName=instanceName&portInfo=portInfo",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Closes the public ports on a specific Amazon Lightsail instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0954e7d3-29aa-41df-aae3-550559f4a696"
            }
          ]
        },
        {
          "id": "cdb45f4a-0d19-4ac2-b60d-fd594c0ad61d",
          "name": "createInstances",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstances?availabilityZone=availabilityZone&blueprintId=blueprintId&bundleId=bundleId&customImageName=customImageName&instanceNames=instanceNames&keyPairName=keyPairName&userData=userData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates one or more Amazon Lightsail virtual private servers, or\n        instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e5f0cde-b363-472a-8d81-d8922374d275"
            }
          ]
        },
        {
          "id": "c8bb11f8-0bdb-431f-a7af-e393f11b961e",
          "name": "createInstancesFromSnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstancesFromSnapshot?availabilityZone=availabilityZone&bundleId=bundleId&instanceNames=instanceNames&instanceSnapshotName=instanceSnapshotName&keyPairName=keyPairName&userData=userData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Uses a specific snapshot as a blueprint for creating one or more new instances that are\n      based on that identical configuration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09eeddbf-cccc-4d8c-ade8-7177cd6d9f75"
            }
          ]
        },
        {
          "id": "8f6893d2-5eeb-4341-bf34-da4261a84256",
          "name": "createInstanceSnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstanceSnapshot?instanceName=instanceName&instanceSnapshotName=instanceSnapshotName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a snapshot of a specific virtual private server, or\n        instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6368bbf4-b3a3-4fcf-9577-f66477a12d9e"
            }
          ]
        },
        {
          "id": "be710f10-3d5b-451e-b593-bc3f8d94b063",
          "name": "deleteInstance",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstance?instanceName=instanceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specific Amazon Lightsail virtual private server, or\n        instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "891b31cb-0092-446d-a7b8-36bf18b5848f"
            }
          ]
        },
        {
          "id": "ff45a11f-c994-4bee-970b-6453f16e7e3a",
          "name": "deleteInstanceSnapshot",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstanceSnapshot?instanceSnapshotName=instanceSnapshotName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specific snapshot of a virtual private server (or\n        instance)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96974fa9-e3e4-4b7a-822e-6573b76611ec"
            }
          ]
        },
        {
          "id": "bab69e26-cb85-408f-bd56-59bff4af146d",
          "name": "getBlueprints",
          "request": {
            "url": "http://example.com/api/?Action=GetBlueprints?includeInactive=includeInactive&pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of available instance images, or blueprints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb3b43d3-93e6-4de7-9033-fbd4801557d4"
            }
          ]
        },
        {
          "id": "66e7aa88-0855-414a-a94c-349ef14e7ffb",
          "name": "getInstance",
          "request": {
            "url": "http://example.com/api/?Action=GetInstance?instanceName=instanceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a specific Amazon Lightsail instance, which is a virtual\n      private server."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aecbaf82-fb25-4e7c-8a49-5bf60fe488a4"
            }
          ]
        },
        {
          "id": "6b916599-bbfa-4d8a-86d9-1d06fdf7d182",
          "name": "getInstanceAccessDetails",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceAccessDetails?instanceName=instanceName&protocol=protocol",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns temporary SSH keys you can use to connect to a specific virtual private server,\n      or instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18ee1a73-7334-4cdf-8396-4a17fc51a0b7"
            }
          ]
        },
        {
          "id": "ac0cf642-db0b-482d-9231-6ff5a744f778",
          "name": "getInstanceMetricData",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceMetricData?endTime=endTime&instanceName=instanceName&metricName=metricName&period=period&startTime=startTime&statistics=statistics&unit=unit",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the data points for the specified Amazon Lightsail instance metric, given an\n      instance name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "500ff2f5-f9ed-4d68-91a1-4187c847b40b"
            }
          ]
        },
        {
          "id": "aea2f8e2-186d-462b-b835-a3a726c5cffc",
          "name": "getInstancePortStates",
          "request": {
            "url": "http://example.com/api/?Action=GetInstancePortStates?instanceName=instanceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the port states for a specific virtual private server, or\n        instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "daa271b4-cdfe-4d70-a1f4-0d3cf7ad2548"
            }
          ]
        },
        {
          "id": "a49bcb37-b58d-4f6b-a24d-3571e4ca3c61",
          "name": "getInstances",
          "request": {
            "url": "http://example.com/api/?Action=GetInstances?pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about all Amazon Lightsail virtual private servers, or\n        instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2bd6f3aa-6f55-4372-87eb-663c319fd1ef"
            }
          ]
        },
        {
          "id": "77e2abab-9c90-4a85-bcb9-7bca1e0c6f95",
          "name": "getInstanceSnapshot",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceSnapshot?instanceSnapshotName=instanceSnapshotName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a specific instance snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5864148-7bd0-4209-82d0-70aa9d73e7b7"
            }
          ]
        },
        {
          "id": "c59a8fbd-ee26-45e6-b287-991a3a2085c4",
          "name": "getInstanceSnapshots",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceSnapshots?pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all instance snapshots for the user's account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "888dfa11-d01d-4118-9aa6-54163d984b87"
            }
          ]
        },
        {
          "id": "02584757-1bad-45f0-9e5e-70e88bfa539b",
          "name": "getInstanceState",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceState?instanceName=instanceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the state of a specific instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db84e496-632f-466f-b0b1-c26ac62e9276"
            }
          ]
        },
        {
          "id": "8da5de18-0f2d-4111-b3c3-c64f6a09ad01",
          "name": "openInstancePublicPorts",
          "request": {
            "url": "http://example.com/api/?Action=OpenInstancePublicPorts?instanceName=instanceName&portInfo=portInfo",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds public ports to an Amazon Lightsail instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c7ed6151-c683-461f-8c22-126c29054b30"
            }
          ]
        },
        {
          "id": "af953d4f-010f-48c8-aacd-2e9df0b9e6c8",
          "name": "rebootInstance",
          "request": {
            "url": "http://example.com/api/?Action=RebootInstance?instanceName=instanceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Restarts a specific instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa8e49bf-68bf-498b-81da-c94c5d7f3007"
            }
          ]
        },
        {
          "id": "489a9995-b1d1-4442-8855-f828cd854a7d",
          "name": "startInstance",
          "request": {
            "url": "http://example.com/api/?Action=StartInstance?instanceName=instanceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a specific Amazon Lightsail instance from a stopped state."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0525d4d-4b50-4c97-8e02-6bd8622ebdd8"
            }
          ]
        },
        {
          "id": "f6dae176-d717-4a1e-b441-1f8d4aa4ff13",
          "name": "stopInstance",
          "request": {
            "url": "http://example.com/api/?Action=StopInstance?instanceName=instanceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops a specific Amazon Lightsail instance that is currently running."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f562d40-f286-405b-9091-8fe7585ae8e5"
            }
          ]
        }
      ]
    },
    {
      "name": "Domains",
      "item": [
        {
          "id": "712be7c4-0ab0-4a5e-bdb7-e74b61667857",
          "name": "createDomain",
          "request": {
            "url": "http://example.com/api/?Action=CreateDomain?domainName=domainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a domain resource for the specified domain (e."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2213383-659a-463b-b4e4-47cd7235b1fe"
            }
          ]
        },
        {
          "id": "7ec922a2-0227-475c-97cc-0ea6f37d225b",
          "name": "createDomainEntry",
          "request": {
            "url": "http://example.com/api/?Action=CreateDomainEntry?domainEntry=domainEntry&domainName=domainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates one of the following entry records associated with the domain: A record, CNAME\n      record, TXT record, or MX record."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39ae2d33-7173-49db-9597-20ccc6dd0f48"
            }
          ]
        },
        {
          "id": "a5eb4f7e-3e27-45f4-b962-3148a9f0e4fe",
          "name": "deleteDomain",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDomain?domainName=domainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified domain recordset and all of its domain records."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f2a7638-5efb-4300-bd37-6cffcb380d47"
            }
          ]
        },
        {
          "id": "1a9fbebb-1283-48ff-bf73-8be0c4f0c8a1",
          "name": "deleteDomainEntry",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDomainEntry?domainEntry=domainEntry&domainName=domainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specific domain entry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c278aab4-712f-48a8-99c5-6c420b48368f"
            }
          ]
        },
        {
          "id": "a3f4704a-3494-43be-8ec6-55cc5ba1c64e",
          "name": "getDomain",
          "request": {
            "url": "http://example.com/api/?Action=GetDomain?domainName=domainName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a specific domain recordset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05c59017-32b7-47a7-b2df-9ee9e9c13b75"
            }
          ]
        },
        {
          "id": "159c9f22-1018-4a2b-8d3c-d5072e4bffdd",
          "name": "getDomains",
          "request": {
            "url": "http://example.com/api/?Action=GetDomains?pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of all domains in the user's account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1959a3f-6de0-4e1a-a1f4-41bdc90a35cd"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Pairs",
      "item": [
        {
          "id": "625b20d2-4349-4134-b4fb-b9e998e9ffdd",
          "name": "createKeyPair",
          "request": {
            "url": "http://example.com/api/?Action=CreateKeyPair?keyPairName=keyPairName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates sn SSH key pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f252806-e46f-457b-952a-c8cb73844a50"
            }
          ]
        },
        {
          "id": "d29aafe0-b6ab-48c0-b4be-b676c333a686",
          "name": "deleteKeyPair",
          "request": {
            "url": "http://example.com/api/?Action=DeleteKeyPair?keyPairName=keyPairName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specific SSH key pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09a85c13-daac-455c-a86d-b775ef9e8308"
            }
          ]
        },
        {
          "id": "8cf7fca9-f912-4d68-95b0-97532691a2c2",
          "name": "downloadDefaultKeyPair",
          "request": {
            "url": "http://example.com/api/?Action=DownloadDefaultKeyPair?privateKeyBase64=privateKeyBase64&publicKeyBase64=publicKeyBase64",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Downloads the default SSH key pair from the user's account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "573f761a-2219-4f57-84c7-7eb58f690581"
            }
          ]
        },
        {
          "id": "6f60a2ee-88f6-4094-83d3-924ffe0d69ae",
          "name": "getKeyPair",
          "request": {
            "url": "http://example.com/api/?Action=GetKeyPair?keyPairName=keyPairName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a specific key pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6ad12bc-264f-4789-b7ce-d898a22a6260"
            }
          ]
        },
        {
          "id": "04eeb8c6-3ab7-43fe-9a50-7c3b9abf3667",
          "name": "getKeyPairs",
          "request": {
            "url": "http://example.com/api/?Action=GetKeyPairs?pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about all key pairs in the user's account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ccb4163-15ff-4a21-b632-451eb0dd52d5"
            }
          ]
        },
        {
          "id": "f01fd79e-92b6-4180-b553-e539c0e3e81a",
          "name": "importKeyPair",
          "request": {
            "url": "http://example.com/api/?Action=ImportKeyPair?keyPairName=keyPairName&publicKeyBase64=publicKeyBase64",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Imports a public SSH key from a specific key pair."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd9138a4-79fb-422b-9fb7-f463f8e0a2b6"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "1b374669-2f67-4a2a-8318-e2011008c8a4",
          "name": "getActiveNames",
          "request": {
            "url": "http://example.com/api/?Action=GetActiveNames?pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the names of all active (not deleted) resources."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c61f05ab-a198-46a9-a252-75a389b9936e"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "da8ebcaf-1d54-4669-910d-9c0fad1b9e29",
          "name": "getBundles",
          "request": {
            "url": "http://example.com/api/?Action=GetBundles?includeInactive=includeInactive&pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of bundles that are available for purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38c47139-7030-4d6b-9281-7101e11c6d04"
            }
          ]
        }
      ]
    },
    {
      "name": "Operations",
      "item": [
        {
          "id": "83639769-58c7-463f-a693-56036564ea95",
          "name": "getOperation",
          "request": {
            "url": "http://example.com/api/?Action=GetOperation?operationId=operationId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a specific operation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9923eec-7821-4f48-b919-8b74ababb372"
            }
          ]
        },
        {
          "id": "775c9a88-77bb-4122-b66c-e61dc3de922b",
          "name": "getOperations",
          "request": {
            "url": "http://example.com/api/?Action=GetOperations?pageToken=pageToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about all operations."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ed629615-9155-4a11-900f-5ac38ffa3972"
            }
          ]
        },
        {
          "id": "2c378853-fa16-47c6-8237-e926b056405e",
          "name": "getOperationsForResource",
          "request": {
            "url": "http://example.com/api/?Action=GetOperationsForResource?pageToken=pageToken&resourceName=resourceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets operations for a specific resource (e."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bbc70fdb-b5af-4160-93f4-0c9144502e89"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "c507d6a6-0276-4103-bdf9-142b18903e84",
          "name": "getRegions",
          "request": {
            "url": "http://example.com/api/?Action=GetRegions?includeAvailabilityZones=includeAvailabilityZones",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of all valid regions for Amazon Lightsail."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5adea256-d867-40cd-a13c-c23510002d15"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "9a584682-5c54-4580-8d72-12e446a40b5b",
          "name": "isVpcPeered",
          "request": {
            "url": "http://example.com/api/?Action=IsVpcPeered?isPeered=isPeered",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a Boolean value indicating whether your Lightsail VPC is peered."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "749b1c39-445e-442e-97d8-76152549fe0d"
            }
          ]
        },
        {
          "id": "7f503936-96a6-428d-ab63-c82f12820b45",
          "name": "peerVpc",
          "request": {
            "url": "http://example.com/api/?Action=PeerVpc?operation=operation",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Tries to peer the Lightsail VPC with the user's default VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06de9cc6-5c21-4a9e-bc64-a9bdc68433d5"
            }
          ]
        },
        {
          "id": "a9b022a7-cf24-4347-b2b2-a34cee611cf9",
          "name": "unpeerVpc",
          "request": {
            "url": "http://example.com/api/?Action=UnpeerVpc?operation=operation",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attempts to unpeer the Lightsail VPC from the user's default VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0bca7869-85d6-4c4c-9c9e-eaeb858bf8a6"
            }
          ]
        }
      ]
    }
  ]
}