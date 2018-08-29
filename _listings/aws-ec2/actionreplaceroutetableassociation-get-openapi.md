---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Replace Route Table Association
  version: 1.0.0
  description: Changes the route table associated with a given subnet in a VPC.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeVpcClassicLink:
    get:
      summary: Describe Vpc Classic Link
      description: Describes the ClassicLink status of one or more VPCs.
      operationId: describevpcclassiclink
      x-api-path-slug: actiondescribevpcclassiclink-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcIds.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DetachClassicLinkVpc:
    get:
      summary: Detach Classic Link Vpc
      description: Unlinks (detaches) a linked EC2-Classic instance from a VPC.
      operationId: detachclassiclinkvpc
      x-api-path-slug: actiondetachclassiclinkvpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DisableVpcClassicLink:
    get:
      summary: Disable Vpc Classic Link
      description: Disables ClassicLink for a VPC.
      operationId: disablevpcclassiclink
      x-api-path-slug: actiondisablevpcclassiclink-get
      parameters:
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=EnableVpcClassicLink:
    get:
      summary: Enable Vpc Classic Link
      description: Enables a VPC for ClassicLink.
      operationId: enablevpcclassiclink
      x-api-path-slug: actionenablevpcclassiclink-get
      parameters:
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=CreateVpc:
    get:
      summary: Create Vpc
      description: Creates a VPC with the specified IPv4 CIDR block.
      operationId: createvpc
      x-api-path-slug: actioncreatevpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DeleteVpc:
    get:
      summary: Delete Vpc
      description: Deletes the specified VPC.
      operationId: deletevpc
      x-api-path-slug: actiondeletevpc-get
      parameters:
      - in: query
        name: Attribute
        description: The VPC attribute
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpcAttribute:
    get:
      summary: Describe Vpc Attribute
      description: Describes the specified attribute of the specified VPC.
      operationId: describevpcattribute
      x-api-path-slug: actiondescribevpcattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcId.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpcs:
    get:
      summary: Describe Vpcs
      description: Describes one or more of your VPCs.
      operationId: describevpcs
      x-api-path-slug: actiondescribevpcs-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID for the CIDR block
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=ModifyVpcAttribute:
    get:
      summary: Modify Vpc Attribute
      description: Modifies the specified attribute of the specified VPC.
      operationId: modifyvpcattribute
      x-api-path-slug: actionmodifyvpcattribute-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the request
        type: string
      - in: query
        name: DeliverLogsPermissionArn
        description: The ARN for the IAM role thats used to post flow logs to a CloudWatch
          Logs log group
        type: string
      - in: query
        name: LogGroupName
        description: The name of the CloudWatch log group
        type: string
      - in: query
        name: ResourceId.N
        description: One or more subnet, network interface, or VPC IDs
        type: string
      - in: query
        name: ResourceType
        description: The type of resource on which to create the flow log
        type: string
      - in: query
        name: TrafficType
        description: The type of traffic to log
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=AcceptVpcPeeringConnection:
    get:
      summary: Accept Vpc Peering Connection
      description: Accept a VPC peering connection request.
      operationId: acceptvpcpeeringconnection
      x-api-path-slug: actionacceptvpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: PeerOwnerId
        description: The AWS account ID of the owner of the peer VPC
        type: string
      - in: query
        name: PeerVpcId
        description: The ID of the VPC with which you are creating the VPC peering
          connection
        type: string
      - in: query
        name: VpcId
        description: The ID of the requester VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=AssociateDhcpOptions:
    get:
      summary: Associate Dhcp Options
      description: Associates a set of DHCP options (that you've previously created)
        with the specified VPC, or associates no DHCP options with the VPC.
      operationId: associatedhcpoptions
      x-api-path-slug: actionassociatedhcpoptions-get
      parameters:
      - in: query
        name: DhcpConfiguration.N
        description: A DHCP configuration option
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - DHCP
  /?Action=AssociateVpcCidrBlock:
    get:
      summary: Associate Vpc Cidr Block
      description: Associates a CIDR block with your VPC.
      operationId: associatevpccidrblock
      x-api-path-slug: actionassociatevpccidrblock-get
      parameters:
      - in: query
        name: AmazonProvidedIpv6CidrBlock
        description: Requests an Amazon-provided IPv6 CIDR block with a /56 prefix
          length for the VPC
        type: string
      - in: query
        name: CidrBlock
        description: The IPv4 network range for the VPC, in CIDR notation
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceTenancy
        description: The tenancy options for instances launched into the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - CIDR Block
  /?Action=AttachClassicLinkVpc:
    get:
      summary: Attach Classic Link Vpc
      description: "Links an EC2-Classic instance to a ClassicLink-enabled VPC through
        one or more of the VPC's\n\t\t\tsecurity groups."
      operationId: attachclassiclinkvpc
      x-api-path-slug: actionattachclassiclinkvpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InstanceId.N
        description: One or more instance IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Link
  /?Action=AttachInternetGateway:
    get:
      summary: Attach Internet Gateway
      description: "Attaches an Internet gateway to a VPC, enabling connectivity between
        the Internet\n\t\t\t\tand the VPC."
      operationId: attachinternetgateway
      x-api-path-slug: actionattachinternetgateway-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure the idempotency
          of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC for which to create the egress-only Internet
          gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=AttachVpnGateway:
    get:
      summary: Attach Vpn Gateway
      description: Attaches a virtual private gateway to a VPC.
      operationId: attachvpngateway
      x-api-path-slug: actionattachvpngateway-get
      parameters:
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the virtual private gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Type
        description: The type of VPN connection this virtual private gateway supports
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPN Gateway
  /?Action=AuthorizeSecurityGroupEgress (EC2-VPC only):
    get:
      summary: Authorize Security Group Egress ( E C2- V P C only)
      description: '[EC2-VPC only] Adds one or more egress rules to a security group
        for use with a VPC.'
      operationId: authorizesecuritygroupegress-ec2vpc-only
      x-api-path-slug: actionauthorizesecuritygroupegress-ec2vpc-only-get
      parameters:
      - in: query
        name: CidrIp
        description: The CIDR IPv4 address range
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: FromPort
        description: The start of port range for the TCP and UDP protocols, or an
          ICMP/ICMPv6 type number
        type: string
      - in: query
        name: GroupId
        description: The ID of the security group
        type: string
      - in: query
        name: GroupName
        description: '[EC2-Classic, default VPC] The name of the security group'
        type: string
      - in: query
        name: IpPermissions.N
        description: A set of IP permissions
        type: string
      - in: query
        name: IpProtocol
        description: The IP protocol name (tcp, udp, icmp) or number      (see Protocol
          Numbers)
        type: string
      - in: query
        name: SourceSecurityGroupName
        description: '[EC2-Classic, default VPC] The name of the source security group'
        type: string
      - in: query
        name: SourceSecurityGroupOwnerId
        description: '[EC2-Classic] The AWS account number for the source security
          group, if the source security group is in a different account'
        type: string
      - in: query
        name: ToPort
        description: The end of port range for the TCP and UDP protocols, or an ICMP/ICMPv6
          code number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=CreateDhcpOptions:
    get:
      summary: Create Dhcp Options
      description: Creates a set of DHCP options for your VPC.
      operationId: createdhcpoptions
      x-api-path-slug: actioncreatedhcpoptions-get
      parameters:
      - in: query
        name: DhcpOptionsId
        description: The ID of the DHCP options set
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - DHCP
  /?Action=CreateEgressOnlyInternetGateway:
    get:
      summary: Create Egress Only Internet Gateway
      description: '[IPv6 only] Creates an egress-only Internet gateway for your VPC.'
      operationId: createegressonlyinternetgateway
      x-api-path-slug: actioncreateegressonlyinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=CreateFlowLogs:
    get:
      summary: Create Flow Logs
      description: Creates one or more flow logs to capture IP traffic for a specific
        network interface, subnet, or VPC.
      operationId: createflowlogs
      x-api-path-slug: actioncreateflowlogs-get
      parameters:
      - in: query
        name: FlowLogId.N
        description: One or more flow log IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Flow Logs
  /?Action=CreateInternetGateway:
    get:
      summary: Create Internet Gateway
      description: Creates an Internet gateway for use with a VPC.
      operationId: createinternetgateway
      x-api-path-slug: actioncreateinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: EgressOnlyInternetGatewayId
        description: The ID of the egress-only Internet gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=CreateNetworkAcl:
    get:
      summary: Create Network Acl
      description: Creates a network ACL in a VPC.
      operationId: createnetworkacl
      x-api-path-slug: actioncreatenetworkacl-get
      parameters:
      - in: query
        name: CidrBlock
        description: The IPv4 network range to allow or deny, in CIDR notation (for
          example                172
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Egress
        description: Indicates whether this is an egress rule (rule is applied to
          traffic leaving the subnet)
        type: string
      - in: query
        name: Icmp
        description: 'ICMP protocol: The ICMP or ICMPv6 type and code'
        type: string
      - in: query
        name: Ipv6CidrBlock
        description: The IPv6 network range to allow or deny, in CIDR notation (for
          example                2001:db8:1234:1a00::/64)
        type: string
      - in: query
        name: NetworkAclId
        description: The ID of the network ACL
        type: string
      - in: query
        name: PortRange
        description: 'TCP or UDP protocols: The range of ports the rule applies to'
        type: string
      - in: query
        name: Protocol
        description: The protocol
        type: string
      - in: query
        name: RuleAction
        description: Indicates whether to allow or deny the traffic that matches the
          rule
        type: string
      - in: query
        name: RuleNumber
        description: The rule number for the entry (for example, 100)
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC ACL
  /?Action=CreateRoute:
    get:
      summary: Create Route
      description: Creates a route in a route table within a VPC.
      operationId: createroute
      x-api-path-slug: actioncreateroute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=CreateRouteTable:
    get:
      summary: Create Route Table
      description: Creates a route table for the specified VPC.
      operationId: createroutetable
      x-api-path-slug: actioncreateroutetable-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The IPv4 CIDR range for the route
        type: string
      - in: query
        name: DestinationIpv6CidrBlock
        description: The IPv6 CIDR range for the route
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route Table
  /?Action=CreateSubnet:
    get:
      summary: Create Subnet
      description: Creates a subnet in an existing VPC.
      operationId: createsubnet
      x-api-path-slug: actioncreatesubnet-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: SubnetId
        description: The ID of the subnet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subnet
  /?Action=CreateVpcEndpoint:
    get:
      summary: Create Vpc Endpoint
      description: Creates a VPC endpoint for a specified AWS service.
      operationId: createvpcendpoint
      x-api-path-slug: actioncreatevpcendpoint-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcEndpointId.N
        description: One or more endpoint IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoint
  /?Action=CreateVpcPeeringConnection:
    get:
      summary: Create Vpc Peering Connection
      description: 'Requests a VPC peering connection between two VPCs: a requester
        VPC that you own and a peer VPC with which to create the connection.'
      operationId: createvpcpeeringconnection
      x-api-path-slug: actioncreatevpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=DeleteVpcEndpoints:
    get:
      summary: Delete Vpc Endpoints
      description: Deletes one or more specified VPC endpoints.
      operationId: deletevpcendpoints
      x-api-path-slug: actiondeletevpcendpoints-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: PrefixListId.N
        description: One or more prefix list IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoints
  /?Action=DeleteVpcPeeringConnection:
    get:
      summary: Delete Vpc Peering Connection
      description: Deletes a VPC peering connection.
      operationId: deletevpcpeeringconnection
      x-api-path-slug: actiondeletevpcpeeringconnection-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcPeeringConnectionId.N
        description: One or more VPC peering connection IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=DescribeMovingAddresses:
    get:
      summary: Describe Moving Addresses
      description: Describes your Elastic IP addresses that are being moved to the
        EC2-VPC platform, or that are being restored to the EC2-Classic platform.
      operationId: describemovingaddresses
      x-api-path-slug: actiondescribemovingaddresses-get
      parameters:
      - in: query
        name: AssociationId
        description: '[EC2-VPC] The association ID'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: PublicIp
        description: '[EC2-Classic] The Elastic IP address'
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=DescribeSecurityGroupReferences (EC2-VPC only):
    get:
      summary: Describe Security Group References ( E C2- V P C only)
      description: '[EC2-VPC only] Describes the VPCs on the other side of a VPC peering
        connection that are referencing the security groups you''ve specified in this
        request.'
      operationId: describesecuritygroupreferences-ec2vpc-only
      x-api-path-slug: actiondescribesecuritygroupreferences-ec2vpc-only-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: GroupId.N
        description: One or more security group IDs
        type: string
      - in: query
        name: GroupName.N
        description: '[EC2-Classic and default VPC only] One or more security group
          names'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Group
  /?Action=DescribeStaleSecurityGroups (EC2-VPC only):
    get:
      summary: Describe Stale Security Groups ( E C2- V P C only)
      description: '[EC2-VPC only] Describes the stale security group rules for security
        groups in a specified VPC.'
      operationId: describestalesecuritygroups-ec2vpc-only
      x-api-path-slug: actiondescribestalesecuritygroups-ec2vpc-only-get
      parameters:
      - in: query
        name: CidrIp
        description: The CIDR IP address range
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: FromPort
        description: The start of port range for the TCP and UDP protocols, or an
          ICMP type number
        type: string
      - in: query
        name: GroupId
        description: The ID of the security group
        type: string
      - in: query
        name: IpPermissions.N
        description: A set of IP permissions
        type: string
      - in: query
        name: IpProtocol
        description: The IP protocol name or number
        type: string
      - in: query
        name: SourceSecurityGroupName
        description: The name of a destination security group
        type: string
      - in: query
        name: SourceSecurityGroupOwnerId
        description: The AWS account number for a destination security group
        type: string
      - in: query
        name: ToPort
        description: The end of port range for the TCP and UDP protocols, or an ICMP
          type number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
  /?Action=DescribeVpcClassicLinkDnsSupport:
    get:
      summary: Describe Vpc Classic Link Dns Support
      description: Describes the ClassicLink DNS support status of one or more VPCs.
      operationId: describevpcclassiclinkdnssupport
      x-api-path-slug: actiondescribevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to unlink from the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC to which the instance is linked
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC DNS
  /?Action=DescribeVpcEndpoints:
    get:
      summary: Describe Vpc Endpoints
      description: Describes one or more of your VPC endpoints.
      operationId: describevpcendpoints
      x-api-path-slug: actiondescribevpcendpoints-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoints
  /?Action=DescribeVpcEndpointServices:
    get:
      summary: Describe Vpc Endpoint Services
      description: Describes all supported AWS services that can be specified when
        creating a VPC endpoint.
      operationId: describevpcendpointservices
      x-api-path-slug: actiondescribevpcendpointservices-get
      parameters:
      - in: query
        name: AddRouteTableId.N
        description: One or more route tables IDs to associate with the endpoint
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: PolicyDocument
        description: A policy document to attach to the endpoint
        type: string
      - in: query
        name: RemoveRouteTableId.N
        description: One or more route table IDs to disassociate from the endpoint
        type: string
      - in: query
        name: ResetPolicy
        description: Specify true to reset the policy document to the default policy
        type: string
      - in: query
        name: VpcEndpointId
        description: The ID of the endpoint
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoint Services
  /?Action=DescribeVpcPeeringConnections:
    get:
      summary: Describe Vpc Peering Connections
      description: Describes one or more of your VPC peering connections.
      operationId: describevpcpeeringconnections
      x-api-path-slug: actiondescribevpcpeeringconnections-get
      parameters:
      - in: query
        name: AccepterPeeringConnectionOptions
        description: The VPC peering connection options for the accepter VPC
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the operation,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: RequesterPeeringConnectionOptions
        description: The VPC peering connection options for the requester VPC
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connections
  /?Action=DetachInternetGateway:
    get:
      summary: Detach Internet Gateway
      description: Detaches an Internet gateway from a VPC, disabling connectivity
        between the Internet and the VPC.
      operationId: detachinternetgateway
      x-api-path-slug: actiondetachinternetgateway-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: KeyName
        description: A unique name for the key pair
        type: string
      responses:
        200:
          description: OK
      tags:
      - Internet Gateway
  /?Action=DisableVgwRoutePropagation:
    get:
      summary: Disable Vgw Route Propagation
      description: Disables a virtual private gateway (VGW) from propagating routes
        to a specified route table of a VPC.
      operationId: disablevgwroutepropagation
      x-api-path-slug: actiondisablevgwroutepropagation-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID representing the current association between
          the route table and subnet
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual Private Gateway
  /?Action=DisableVpcClassicLinkDnsSupport:
    get:
      summary: Disable Vpc Classic Link Dns Support
      description: Disables ClassicLink DNS support for a VPC.
      operationId: disablevpcclassiclinkdnssupport
      x-api-path-slug: actiondisablevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC DNS
  /?Action=DisassociateVpcCidrBlock:
    get:
      summary: Disassociate Vpc Cidr Block
      description: Disassociates a CIDR block from a VPC.
      operationId: disassociatevpccidrblock
      x-api-path-slug: actiondisassociatevpccidrblock-get
      parameters:
      - in: query
        name: EnableDnsHostnames
        description: Indicates whether the instances launched in the VPC get DNS hostnames
        type: string
      - in: query
        name: EnableDnsSupport
        description: Indicates whether the DNS resolution is supported for the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - CIDR Block
  /?Action=EnableVgwRoutePropagation:
    get:
      summary: Enable Vgw Route Propagation
      description: Enables a virtual private gateway (VGW) to propagate routes to
        the specified route table of a VPC.
      operationId: enablevgwroutepropagation
      x-api-path-slug: actionenablevgwroutepropagation-get
      parameters:
      - in: query
        name: DestinationCidrBlock
        description: The IPv4 CIDR address block used for the destination match
        type: string
      - in: query
        name: DestinationIpv6CidrBlock
        description: The IPv6 CIDR address block used for the destination match
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EgressOnlyInternetGatewayId
        description: '[IPv6 traffic only] The ID of an egress-only Internet gateway'
        type: string
      - in: query
        name: GatewayId
        description: The ID of an Internet gateway or virtual private gateway
        type: string
      - in: query
        name: InstanceId
        description: The ID of a NAT instance in your VPC
        type: string
      - in: query
        name: NatGatewayId
        description: '[IPv4 traffic only] The ID of a NAT gateway'
        type: string
      - in: query
        name: NetworkInterfaceId
        description: The ID of a network interface
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the route table
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of a VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Virtual Private Gateway Route Propogation
  /?Action=EnableVpcClassicLinkDnsSupport:
    get:
      summary: Enable Vpc Classic Link Dns Support
      description: Enables a VPC to support DNS hostname resolution for ClassicLink.
      operationId: enablevpcclassiclinkdnssupport
      x-api-path-slug: actionenablevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: BgpAsn
        description: For devices that support BGP, the customer gateways BGP ASN
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: IpAddress
        description: The Internet-routable IP address for the customer gateways outside
          interface
        type: string
      - in: query
        name: Type
        description: The type of VPN connection that this customer gateway supports
          (ipsec
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC NS
  /?Action=ModifyReservedInstances:
    get:
      summary: Modify Reserved Instances
      description: Modifies the Availability Zone, instance count, instance type,
        or network platform (EC2-Classic or EC2-VPC) of your Standard Reserved Instances.
      operationId: modifyreservedinstances
      x-api-path-slug: actionmodifyreservedinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceCount
        description: The number of Reserved Instances to purchase
        type: string
      - in: query
        name: LimitPrice
        description: Specified for Reserved Instance Marketplace offerings to limit
          the total order and ensure that the Reserved Instances are not purchased
          at unexpected prices
        type: string
      - in: query
        name: ReservedInstancesOfferingId
        description: The ID of the Reserved Instance offering to purchase
        type: string
      responses:
        200:
          description: OK
      tags:
      - Reserved Instance
  /?Action=ModifyVpcEndpoint:
    get:
      summary: Modify Vpc Endpoint
      description: Modifies attributes of a specified VPC endpoint.
      operationId: modifyvpcendpoint
      x-api-path-slug: actionmodifyvpcendpoint-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Endpoint
  /?Action=ModifyVpcPeeringConnectionOptions:
    get:
      summary: Modify Vpc Peering Connection Options
      description: Modifies the VPC peering connection options on one side of a VPC
        peering connection.
      operationId: modifyvpcpeeringconnectionoptions
      x-api-path-slug: actionmodifyvpcpeeringconnectionoptions-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: VpcPeeringConnectionId
        description: The ID of the VPC peering connection
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=MoveAddressToVpc:
    get:
      summary: Move Address To Vpc
      description: Moves an Elastic IP address from the EC2-Classic platform to the
        EC2-VPC platform.
      operationId: moveaddresstovpc
      x-api-path-slug: actionmoveaddresstovpc-get
      parameters:
      - in: query
        name: AllocationId
        description: '[EC2-VPC] The allocation ID'
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: PublicIp
        description: '[EC2-Classic] The Elastic IP address'
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Address
  /?Action=RejectVpcPeeringConnection:
    get:
      summary: Reject Vpc Peering Connection
      description: Rejects a VPC peering connection request.
      operationId: rejectvpcpeeringconnection
      x-api-path-slug: actionrejectvpcpeeringconnection-get
      parameters:
      - in: query
        name: CustomerGatewayId
        description: The ID of the customer gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Options
        description: Indicates whether the VPN connection requires static routes
        type: string
      - in: query
        name: Type
        description: The type of VPN connection (ipsec
        type: string
      - in: query
        name: VpnGatewayId
        description: The ID of the virtual private gateway
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Peering Connection
  /?Action=ReplaceRoute:
    get:
      summary: Replace Route
      description: Replaces an existing route within a route table in a VPC.
      operationId: replaceroute
      x-api-path-slug: actionreplaceroute-get
      parameters:
      - in: query
        name: AssociationId
        description: The association ID
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: RouteTableId
        description: The ID of the new route table to associate with the subnet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Route
  /?Action=ReplaceRouteTableAssociation:
    get:
      summary: Replace Route Table Association
      description: Changes the route table associated with a given subnet in a VPC.
      operationId: replaceroutetableassociation
      x-api-path-slug: actionreplaceroutetableassociation-get
      responses:
        200:
          description: OK
      tags:
      - Route Table
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---