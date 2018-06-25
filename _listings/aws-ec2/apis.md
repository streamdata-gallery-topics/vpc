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
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/apis.md
specificationVersion: "0.14"
apis:
- name: AWS EC2 API Attach Classic Link Vpc
  x-api-slug: aws-ec2-api
  description: "Links an EC2-Classic instance to a ClassicLink-enabled VPC through
    one or more of the VPC's\n\t\t\tsecurity groups."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AttachClassicLinkVpc
  tags: VPC Link
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachclassiclinkvpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionattachclassiclinkvpc-get-openapi.md
- name: AWS EC2 API Describe Vpc Classic Link
  x-api-slug: aws-ec2-api
  description: Describes the ClassicLink status of one or more VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcClassicLink
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcclassiclink-get-openapi.md
- name: AWS EC2 API Describe Vpc Classic Link Dns Support
  x-api-slug: aws-ec2-api
  description: Describes the ClassicLink DNS support status of one or more VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcClassicLinkDnsSupport
  tags: VPC DNS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API Detach Classic Link Vpc
  x-api-slug: aws-ec2-api
  description: Unlinks (detaches) a linked EC2-Classic instance from a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DetachClassicLinkVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondetachclassiclinkvpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondetachclassiclinkvpc-get-openapi.md
- name: AWS EC2 API Disable Vpc Classic Link
  x-api-slug: aws-ec2-api
  description: Disables ClassicLink for a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisableVpcClassicLink
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevpcclassiclink-get-openapi.md
- name: AWS EC2 API Disable Vpc Classic Link Dns Support
  x-api-slug: aws-ec2-api
  description: Disables ClassicLink DNS support for a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DisableVpcClassicLinkDnsSupport
  tags: VPC DNS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondisablevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API Enable Vpc Classic Link
  x-api-slug: aws-ec2-api
  description: Enables a VPC for ClassicLink.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=EnableVpcClassicLink
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclink-get-openapi.md
- name: AWS EC2 API Enable Vpc Classic Link Dns Support
  x-api-slug: aws-ec2-api
  description: Enables a VPC to support DNS hostname resolution for ClassicLink.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=EnableVpcClassicLinkDnsSupport
  tags: VPC NS
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclinkdnssupport-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionenablevpcclassiclinkdnssupport-get-openapi.md
- name: AWS EC2 API Create Network Acl
  x-api-slug: aws-ec2-api
  description: Creates a network ACL in a VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateNetworkAcl
  tags: VPC ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatenetworkacl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatenetworkacl-get-openapi.md
- name: AWS EC2 API Create Network Acl Entry
  x-api-slug: aws-ec2-api
  description: Creates an entry (a rule) in a network ACL with the specified rule
    number.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateNetworkAclEntry
  tags: VPC ACL
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatenetworkaclentry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatenetworkaclentry-get-openapi.md
- name: AWS EC2 API Create Vpc
  x-api-slug: aws-ec2-api
  description: Creates a VPC with the specified IPv4 CIDR block.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpc-get-openapi.md
- name: AWS EC2 API Delete Vpc
  x-api-slug: aws-ec2-api
  description: Deletes the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpc
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpc-get-openapi.md
- name: AWS EC2 API Describe Vpc Attribute
  x-api-slug: aws-ec2-api
  description: Describes the specified attribute of the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcAttribute
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcattribute-get-openapi.md
- name: AWS EC2 API Describe Vpcs
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPCs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcs
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcs-get-openapi.md
- name: AWS EC2 API Modify Vpc Attribute
  x-api-slug: aws-ec2-api
  description: Modifies the specified attribute of the specified VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVpcAttribute
  tags: VPC
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcattribute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcattribute-get-openapi.md
- name: AWS EC2 API Create Vpc Endpoint
  x-api-slug: aws-ec2-api
  description: Creates a VPC endpoint for a specified AWS service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpcEndpoint
  tags: VPC Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcendpoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcendpoint-get-openapi.md
- name: AWS EC2 API Delete Vpc Endpoints
  x-api-slug: aws-ec2-api
  description: Deletes one or more specified VPC endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpcEndpoints
  tags: VPC Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpcendpoints-get-openapi.md
- name: AWS EC2 API Describe Vpc Endpoints
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPC endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcEndpoints
  tags: VPC Endpoints
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcendpoints-get-openapi.md
- name: AWS EC2 API Describe Vpc Endpoint Services
  x-api-slug: aws-ec2-api
  description: Describes all supported AWS services that can be specified when creating
    a VPC endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcEndpointServices
  tags: VPC Endpoint Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcendpointservices-get-openapi.md
- name: AWS EC2 API Modify Vpc Endpoint
  x-api-slug: aws-ec2-api
  description: Modifies attributes of a specified VPC endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVpcEndpoint
  tags: VPC Endpoint
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcendpoint-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcendpoint-get-openapi.md
- name: AWS EC2 API Accept Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: Accept a VPC peering connection request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=AcceptVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionacceptvpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionacceptvpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Create Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: 'Requests a VPC peering connection between two VPCs: a requester VPC
    that you own and a peer VPC with which to create the connection.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Delete Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: Deletes a VPC peering connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DeleteVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondeletevpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Describe Vpc Peering Connections
  x-api-slug: aws-ec2-api
  description: Describes one or more of your VPC peering connections.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=DescribeVpcPeeringConnections
  tags: VPC Peering Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actiondescribevpcpeeringconnections-get-openapi.md
- name: AWS EC2 API Modify Vpc Peering Connection Options
  x-api-slug: aws-ec2-api
  description: Modifies the VPC peering connection options on one side of a VPC peering
    connection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=ModifyVpcPeeringConnectionOptions
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcpeeringconnectionoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionmodifyvpcpeeringconnectionoptions-get-openapi.md
- name: AWS EC2 API Reject Vpc Peering Connection
  x-api-slug: aws-ec2-api
  description: Rejects a VPC peering connection request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=RejectVpcPeeringConnection
  tags: VPC Peering Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionrejectvpcpeeringconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actionrejectvpcpeeringconnection-get-openapi.md
- name: AWS EC2 API Create Vpn Connection
  x-api-slug: aws-ec2-api
  description: |-
    Creates a VPN connection between an existing virtual private gateway and a VPN customer
                gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpnConnection
  tags: VPC Connection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpnconnection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpnconnection-get-openapi.md
- name: AWS EC2 API Create Vpn Connection Route
  x-api-slug: aws-ec2-api
  description: Creates a static route associated with a VPN connection between an
    existing virtual private gateway and a VPN customer gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: ://///?Action=CreateVpnConnectionRoute
  tags: VPC Connection Route
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpnconnectionroute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/actioncreatevpnconnectionroute-get-openapi.md
- name: AWS EC2 API
  x-api-slug: aws-ec2-api
  description: Amazon Elastic Compute Cloud is a web service that provides resizable
    compute capacity in the cloud. It is designed to make web-scale cloud computing
    easier for developers. Amazon EC2s simple web service interface allows you to
    obtain and configure capacity with minimal friction. It provides you with complete
    control of your computing resources and lets you run on Amazon&rsquo;s proven
    computing environment. Amazon EC2 reduces the time required to obtain and boot
    new server instances to minutes, allowing you to quickly scale capacity, both
    up and down, as your computing requirements change. Amazon EC2 changes the economics
    of computing by allowing you to pay only for capacity that you actually use. Amazon
    EC2 provides developers the tools to build failure resilient applications and
    isolate themselves from common failure scenarios.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AmazonEC2.png
  humanURL: https://aws.amazon.com/ec2/
  baseURL: :///
  tags: VPC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-ec2/openapi.md
x-common:
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