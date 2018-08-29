---
name: AWS EC2
x-slug: aws-ec2
description: Amazon Elastic Compute Cloud is a web service that provides resizable
  compute capacity in the cloud. It is designed to make web-scale cloud computing
  easier for developers. Amazon EC2s simple web service interface allows you to obtain
  and configure capacity with minimal friction. It provides you with complete control
  of your computing resources and lets you run on Amazon&rsquo;s proven computing
  environment. Amazon EC2 reduces the time required to obtain and boot new server
  instances to minutes, allowing you to quickly scale capacity, both up and down,
  as your computing requirements change. Amazon EC2 changes the economics of computing
  by allowing you to pay only for capacity that you actually use. Amazon EC2 provides
  developers the tools to build failure resilient applications and isolate themselves
  from common failure scenarios.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
x-kinRank: "10"
x-alexaRank: "0"
tags: VPC
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 API - Describe Vpc Classic Link
  x-api-slug: actiondescribevpcclassiclink-get
  description: Describes the ClassicLink status of one or more VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcclassiclink-get-openapi.md
- name: AWS EC2 API - Detach Classic Link Vpc
  x-api-slug: actiondetachclassiclinkvpc-get
  description: Unlinks (detaches) a linked EC2-Classic instance from a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondetachclassiclinkvpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondetachclassiclinkvpc-get-openapi.md
- name: AWS EC2 API - Disable Vpc Classic Link
  x-api-slug: actiondisablevpcclassiclink-get
  description: Disables ClassicLink for a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevpcclassiclink-get-openapi.md
- name: AWS EC2 API - Enable Vpc Classic Link
  x-api-slug: actionenablevpcclassiclink-get
  description: Enables a VPC for ClassicLink.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclink-get-openapi.md
- name: AWS EC2 API - Create Vpc
  x-api-slug: actioncreatevpc-get
  description: Creates a VPC with the specified IPv4 CIDR block.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpc-get-openapi.md
- name: AWS EC2 API - Delete Vpc
  x-api-slug: actiondeletevpc-get
  description: Deletes the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpc-get-openapi.md
- name: AWS EC2 API - Describe Vpc Attribute
  x-api-slug: actiondescribevpcattribute-get
  description: Describes the specified attribute of the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcattribute-get-openapi.md
- name: AWS EC2 API - Describe Vpcs
  x-api-slug: actiondescribevpcs-get
  description: Describes one or more of your VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcs-get-openapi.md
- name: AWS EC2 API - Modify Vpc Attribute
  x-api-slug: actionmodifyvpcattribute-get
  description: Modifies the specified attribute of the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcattribute-get-openapi.md
- name: AWS EC2 API - Accept Vpc Peering Connection
  x-api-slug: actionacceptvpcpeeringconnection-get
  description: Accept a VPC peering connection request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionacceptvpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionacceptvpcpeeringconnection-get-openapi.md
- name: AWS EC2 API - Associate Dhcp Options
  x-api-slug: actionassociatedhcpoptions-get
  description: Associates a set of DHCP options (that you've previously created) with
    the specified VPC, or associates no DHCP options with the VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionassociatedhcpoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionassociatedhcpoptions-get-openapi.md
- name: AWS EC2 API - Associate Vpc Cidr Block
  x-api-slug: actionassociatevpccidrblock-get
  description: Associates a CIDR block with your VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionassociatevpccidrblock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionassociatevpccidrblock-get-openapi.md
- name: AWS EC2 API - Attach Classic Link Vpc
  x-api-slug: actionattachclassiclinkvpc-get
  description: "Links an EC2-Classic instance to a ClassicLink-enabled VPC through
    one or more of the VPC's\n\t\t\tsecurity groups."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachclassiclinkvpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachclassiclinkvpc-get-openapi.md
- name: AWS EC2 API - Attach Internet Gateway
  x-api-slug: actionattachinternetgateway-get
  description: "Attaches an Internet gateway to a VPC, enabling connectivity between
    the Internet\n\t\t\t\tand the VPC."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachinternetgateway-get-openapi.md
- name: AWS EC2 API - Attach Vpn Gateway
  x-api-slug: actionattachvpngateway-get
  description: Attaches a virtual private gateway to a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachvpngateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachvpngateway-get-openapi.md
- name: AWS EC2 API - Authorize Security Group Egress ( E C2- V P C only)
  x-api-slug: actionauthorizesecuritygroupegress-ec2vpc-only-get
  description: '[EC2-VPC only] Adds one or more egress rules to a security group for
    use with a VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionauthorizesecuritygroupegress-ec2vpc-only-get-openapi.md
- name: AWS EC2 API - Create Dhcp Options
  x-api-slug: actioncreatedhcpoptions-get
  description: Creates a set of DHCP options for your VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatedhcpoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatedhcpoptions-get-openapi.md
- name: AWS EC2 API - Create Egress Only Internet Gateway
  x-api-slug: actioncreateegressonlyinternetgateway-get
  description: '[IPv6 only] Creates an egress-only Internet gateway for your VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateegressonlyinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateegressonlyinternetgateway-get-openapi.md
- name: AWS EC2 API - Create Flow Logs
  x-api-slug: actioncreateflowlogs-get
  description: Creates one or more flow logs to capture IP traffic for a specific
    network interface, subnet, or VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateflowlogs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateflowlogs-get-openapi.md
- name: AWS EC2 API - Create Internet Gateway
  x-api-slug: actioncreateinternetgateway-get
  description: Creates an Internet gateway for use with a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateinternetgateway-get-openapi.md
- name: AWS EC2 API - Create Network Acl
  x-api-slug: actioncreatenetworkacl-get
  description: Creates a network ACL in a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatenetworkacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatenetworkacl-get-openapi.md
- name: AWS EC2 API - Create Route
  x-api-slug: actioncreateroute-get
  description: Creates a route in a route table within a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateroute-get-openapi.md
- name: AWS EC2 API - Create Route Table
  x-api-slug: actioncreateroutetable-get
  description: Creates a route table for the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateroutetable-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreateroutetable-get-openapi.md
- name: AWS EC2 API - Create Subnet
  x-api-slug: actioncreatesubnet-get
  description: Creates a subnet in an existing VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatesubnet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatesubnet-get-openapi.md
- name: AWS EC2 API - Create Vpc Endpoint
  x-api-slug: actioncreatevpcendpoint-get
  description: Creates a VPC endpoint for a specified AWS service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcendpoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcendpoint-get-openapi.md
- name: AWS EC2 API - Create Vpc Peering Connection
  x-api-slug: actioncreatevpcpeeringconnection-get
  description: 'Requests a VPC peering connection between two VPCs: a requester VPC
    that you own and a peer VPC with which to create the connection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcpeeringconnection-get-openapi.md
- name: AWS EC2 API - Delete Vpc Endpoints
  x-api-slug: actiondeletevpcendpoints-get
  description: Deletes one or more specified VPC endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpcendpoints-get-openapi.md
- name: AWS EC2 API - Delete Vpc Peering Connection
  x-api-slug: actiondeletevpcpeeringconnection-get
  description: Deletes a VPC peering connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpcpeeringconnection-get-openapi.md
- name: AWS EC2 API - Describe Moving Addresses
  x-api-slug: actiondescribemovingaddresses-get
  description: Describes your Elastic IP addresses that are being moved to the EC2-VPC
    platform, or that are being restored to the EC2-Classic platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribemovingaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribemovingaddresses-get-openapi.md
- name: AWS EC2 API - Describe Security Group References ( E C2- V P C only)
  x-api-slug: actiondescribesecuritygroupreferences-ec2vpc-only-get
  description: '[EC2-VPC only] Describes the VPCs on the other side of a VPC peering
    connection that are referencing the security groups you''ve specified in this
    request.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribesecuritygroupreferences-ec2vpc-only-get-openapi.md
- name: AWS EC2 API - Describe Stale Security Groups ( E C2- V P C only)
  x-api-slug: actiondescribestalesecuritygroups-ec2vpc-only-get
  description: '[EC2-VPC only] Describes the stale security group rules for security
    groups in a specified VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribestalesecuritygroups-ec2vpc-only-get-openapi.md
- name: AWS EC2 API - Describe Vpc Classic Link Dns Support
  x-api-slug: actiondescribevpcclassiclinkdnssupport-get
  description: Describes the ClassicLink DNS support status of one or more VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API - Describe Vpc Endpoints
  x-api-slug: actiondescribevpcendpoints-get
  description: Describes one or more of your VPC endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcendpoints-get-openapi.md
- name: AWS EC2 API - Describe Vpc Endpoint Services
  x-api-slug: actiondescribevpcendpointservices-get
  description: Describes all supported AWS services that can be specified when creating
    a VPC endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcendpointservices-get-openapi.md
- name: AWS EC2 API - Describe Vpc Peering Connections
  x-api-slug: actiondescribevpcpeeringconnections-get
  description: Describes one or more of your VPC peering connections.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcpeeringconnections-get-openapi.md
- name: AWS EC2 API - Detach Internet Gateway
  x-api-slug: actiondetachinternetgateway-get
  description: Detaches an Internet gateway from a VPC, disabling connectivity between
    the Internet and the VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondetachinternetgateway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondetachinternetgateway-get-openapi.md
- name: AWS EC2 API - Disable Vgw Route Propagation
  x-api-slug: actiondisablevgwroutepropagation-get
  description: Disables a virtual private gateway (VGW) from propagating routes to
    a specified route table of a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevgwroutepropagation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevgwroutepropagation-get-openapi.md
- name: AWS EC2 API - Disable Vpc Classic Link Dns Support
  x-api-slug: actiondisablevpcclassiclinkdnssupport-get
  description: Disables ClassicLink DNS support for a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API - Disassociate Vpc Cidr Block
  x-api-slug: actiondisassociatevpccidrblock-get
  description: Disassociates a CIDR block from a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisassociatevpccidrblock-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisassociatevpccidrblock-get-openapi.md
- name: AWS EC2 API - Enable Vgw Route Propagation
  x-api-slug: actionenablevgwroutepropagation-get
  description: Enables a virtual private gateway (VGW) to propagate routes to the
    specified route table of a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevgwroutepropagation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevgwroutepropagation-get-openapi.md
- name: AWS EC2 API - Enable Vpc Classic Link Dns Support
  x-api-slug: actionenablevpcclassiclinkdnssupport-get
  description: Enables a VPC to support DNS hostname resolution for ClassicLink.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclinkdnssupport-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API - Modify Reserved Instances
  x-api-slug: actionmodifyreservedinstances-get
  description: Modifies the Availability Zone, instance count, instance type, or network
    platform (EC2-Classic or EC2-VPC) of your Standard Reserved Instances.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyreservedinstances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyreservedinstances-get-openapi.md
- name: AWS EC2 API - Modify Vpc Endpoint
  x-api-slug: actionmodifyvpcendpoint-get
  description: Modifies attributes of a specified VPC endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcendpoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcendpoint-get-openapi.md
- name: AWS EC2 API - Modify Vpc Peering Connection Options
  x-api-slug: actionmodifyvpcpeeringconnectionoptions-get
  description: Modifies the VPC peering connection options on one side of a VPC peering
    connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcpeeringconnectionoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcpeeringconnectionoptions-get-openapi.md
- name: AWS EC2 API - Move Address To Vpc
  x-api-slug: actionmoveaddresstovpc-get
  description: Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC
    platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmoveaddresstovpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmoveaddresstovpc-get-openapi.md
- name: AWS EC2 API - Reject Vpc Peering Connection
  x-api-slug: actionrejectvpcpeeringconnection-get
  description: Rejects a VPC peering connection request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionrejectvpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionrejectvpcpeeringconnection-get-openapi.md
- name: AWS EC2 API - Replace Route
  x-api-slug: actionreplaceroute-get
  description: Replaces an existing route within a route table in a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionreplaceroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionreplaceroute-get-openapi.md
- name: AWS EC2 API - Replace Route Table Association
  x-api-slug: actionreplaceroutetableassociation-get
  description: Changes the route table associated with a given subnet in a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionreplaceroutetableassociation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionreplaceroutetableassociation-get-openapi.md
- name: AWS EC2 API - Restore Address To Classic
  x-api-slug: actionrestoreaddresstoclassic-get
  description: Restores an Elastic IP address that was previously moved to the EC2-VPC
    platform back to the EC2-Classic platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionrestoreaddresstoclassic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionrestoreaddresstoclassic-get-openapi.md
- name: AWS EC2 API - Revoke Security Group Egress ( E C2- V P C only)
  x-api-slug: actionrevokesecuritygroupegress-ec2vpc-only-get
  description: '[EC2-VPC only] Removes one or more egress rules from a security group
    for EC2-VPC.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: Amazon Web Services, Compute, Stack Network, Stack, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionrevokesecuritygroupegress-ec2vpc-only-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.dynamodb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.ec2.stack.network
- type: x-code
  url: http://aws.amazon.com/code/Amazon-EC2/
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSEC2/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/ec2/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/ec2/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/ec2/pricing/
- type: x-sla
  url: https://aws.amazon.com/ec2/sla/
- type: x-website
  url: https://aws.amazon.com/ec2/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---