{
  "info": {
    "name": "Amazon Lightsale API Peer Vpc",
    "_postman_id": "5a716030-3168-49e2-83d0-0ba874b1daa1",
    "description": "Tries to peer the Lightsail VPC with the user's default VPC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "IP Addresses",
      "item": [
        {
          "id": "72ad0249-ef73-4b72-930f-18f757256305",
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
              "id": "618836a2-5bf6-4f43-adc6-354329346997"
            }
          ]
        },
        {
          "id": "73956a53-36a4-477a-a984-ae1b6049891a",
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
              "id": "2975851c-4f29-4f01-a739-5e7d374d3c68"
            }
          ]
        },
        {
          "id": "b2de6ae8-61e3-4138-85cf-dcae3fc0e198",
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
              "id": "4af7549b-c2f3-409d-958e-cf4da6e166c2"
            }
          ]
        },
        {
          "id": "a63a3bf9-0a4a-4b7d-8371-04b60483bb8a",
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
              "id": "22c26ca7-0e65-4488-8e7a-0ba6cc236929"
            }
          ]
        },
        {
          "id": "659f7bf3-7114-4011-8653-5e7b9c71880a",
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
              "id": "ce0b84de-a898-49b8-9afe-27208132b6ce"
            }
          ]
        }
      ]
    },
    {
      "name": "Instances",
      "item": [
        {
          "id": "bef832fe-c6d1-4d02-a8ff-c4bf79d8ad53",
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
              "id": "10abcd66-9775-4c13-9b6f-36a1067c2d0c"
            }
          ]
        },
        {
          "id": "d0ebfe6a-a91b-49c1-ae1f-c4ccc398f111",
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
              "id": "e81613b7-8d7b-4f2d-86ae-fee1e3a46d5e"
            }
          ]
        },
        {
          "id": "041edec7-97c1-4c71-91d7-37023573b06d",
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
              "id": "5bc935d7-f03b-41c8-abe1-40cb3db0d4e0"
            }
          ]
        },
        {
          "id": "83d6f9cb-b317-4c6a-86c6-dc88341f40a7",
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
              "id": "733c3a3a-5377-4499-b0fd-45c0c52880ca"
            }
          ]
        },
        {
          "id": "ca749396-f932-4a32-b699-96c4d23e99ca",
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
              "id": "c34280cc-47be-4b8a-8fc3-c3dc11d066ea"
            }
          ]
        },
        {
          "id": "6d746f84-9ec4-4307-9ef8-13a3f998b8f3",
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
              "id": "d5393d99-5c91-45a2-bdf9-e1714dfd9cb9"
            }
          ]
        },
        {
          "id": "e0918f65-7ad0-4ee8-8baf-b783f81bb11d",
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
              "id": "f1bfadb9-32a1-43c0-a388-b33275a963c5"
            }
          ]
        },
        {
          "id": "7c8fcdda-a362-4c1d-b01d-7a577909daee",
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
              "id": "ba56b269-b426-4f2a-8dc8-4910a828ed64"
            }
          ]
        },
        {
          "id": "8cfe4613-1af7-4ef5-8f44-90cf67d6e154",
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
              "id": "f6038cfb-f547-4aa4-a13d-372e01c96be8"
            }
          ]
        },
        {
          "id": "9c258dc8-d4ba-494c-9743-93024fbacf61",
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
              "id": "484301df-8c77-43fe-baf5-e1468c978246"
            }
          ]
        },
        {
          "id": "72a209a6-4250-4ed5-a975-f68172d0263d",
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
              "id": "9716e6bb-3235-4e41-a653-3c7d5ad08620"
            }
          ]
        },
        {
          "id": "c24bba9d-8818-4f17-8a95-c97ad5781946",
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
              "id": "7a6884b2-5993-48b0-a9ea-7a923d77cd47"
            }
          ]
        },
        {
          "id": "11d1c85a-5179-49aa-ae32-b2075980a42e",
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
              "id": "c7dc774b-de3a-4525-b22b-448f08a8d16a"
            }
          ]
        },
        {
          "id": "6f172571-6722-4ca9-bf30-64bed4300267",
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
              "id": "881d37c8-ada0-442a-b18d-3c0248eaabf9"
            }
          ]
        },
        {
          "id": "7f1350dc-dc57-4321-aa11-2d1e6d1e2ad2",
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
              "id": "df8fb8a0-374c-49d0-8aff-7b47d75db5f3"
            }
          ]
        },
        {
          "id": "34259cbf-7eb2-469d-a798-f8c3f8ba7dc8",
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
              "id": "7cfc0dd2-a987-4386-a216-df2384fbb6e7"
            }
          ]
        }
      ]
    },
    {
      "name": "Domains",
      "item": [
        {
          "id": "cb4c6d81-989d-4d53-ac2c-4126e82b493e",
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
              "id": "e2025922-f6ae-4880-8b21-04e5c4ea4bc3"
            }
          ]
        },
        {
          "id": "2e955fed-8618-4981-9487-1db12fec71d4",
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
              "id": "eb048c82-d297-48fe-ac45-2bce350de90b"
            }
          ]
        },
        {
          "id": "835baa2c-0109-4433-8c5a-fd7f3ad6ca51",
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
              "id": "5891ff91-1c44-4d76-9b84-be4f60048fd6"
            }
          ]
        },
        {
          "id": "effdb2f9-475e-4ab7-827d-5b5ebbcd1b07",
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
              "id": "d2540931-013f-4f09-a8f1-344f0b0ad274"
            }
          ]
        },
        {
          "id": "385125e4-ae39-4654-ad19-3dfd11e351f5",
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
              "id": "ba08a3da-a718-4290-b0a7-ad064d7e74d1"
            }
          ]
        },
        {
          "id": "322f66e1-028d-4396-be97-0c09e69431fb",
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
              "id": "78e91da3-9d80-444a-80e7-9251eaf7b07e"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Pairs",
      "item": [
        {
          "id": "9d17c3bd-4326-4468-b986-bbb3db4241d1",
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
              "id": "74accc9f-db8a-4b86-afb4-e9e7cbbd1513"
            }
          ]
        },
        {
          "id": "59940afa-c652-471c-9da1-7d3f50296690",
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
              "id": "f69c79c1-6a6e-4e9b-a0e3-1831351f036a"
            }
          ]
        },
        {
          "id": "a28fdba1-eb97-4a6f-999f-f0f1f1adf408",
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
              "id": "7ec6e75e-3206-4f94-98f2-5479a56f3313"
            }
          ]
        },
        {
          "id": "c890f5c0-07cd-401e-9c4e-402999e2867e",
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
              "id": "86560148-675e-49ef-b6fc-dcd3c6a5d506"
            }
          ]
        },
        {
          "id": "a24007fe-305a-478a-8d60-f3b51a4425d5",
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
              "id": "56c195f5-1bda-45c7-9704-188e73633889"
            }
          ]
        },
        {
          "id": "19dc0d91-6ee9-414d-aa6e-e432df241590",
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
              "id": "0ec9add8-e684-4e33-be0b-aef3c9439d0f"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "7d030169-6932-4aed-b6f6-7c29f2e8d0d0",
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
              "id": "fda7ddbf-cc7d-43d3-86b3-15ca515f9082"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "623c2170-920f-4f04-a6de-097069b4d31e",
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
              "id": "d123d297-7f4b-49c2-98cc-1838085dc291"
            }
          ]
        }
      ]
    },
    {
      "name": "Operations",
      "item": [
        {
          "id": "03a804f9-e1d6-4c56-b5f0-2919c4fa9a38",
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
              "id": "d68c920f-df2d-4152-be8d-8cffe947516d"
            }
          ]
        },
        {
          "id": "982d08bd-b0ff-4d4f-b0a8-a09d1f31596e",
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
              "id": "3aa51eaa-a345-4ee5-ab1b-c30afc89e384"
            }
          ]
        },
        {
          "id": "4b57f570-1a1d-4bc6-8bd1-ce999acbc903",
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
              "id": "accab615-bfc3-4101-add5-80aa7cc711d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "bf701ebb-67b1-4f9f-93a5-aaea625cb529",
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
              "id": "45ef7652-5d80-46be-91c2-701c94255fad"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "2bf8680b-5aa2-4b12-aded-87bbb0d9a96d",
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
              "id": "25be7c14-cfd6-4058-9dab-7198a1c97066"
            }
          ]
        },
        {
          "id": "34461a2b-526a-418d-84fe-cc273ab6fb15",
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
              "id": "cb1216f1-5548-498c-b530-4007bc9928f9"
            }
          ]
        }
      ]
    }
  ]
}