---
name: AWS Route 53
x-slug: aws-route-53
description: Amazon Route 53 is a highly available and scalable cloud Domain Name
  System (DNS) web service. It is designed to give developers and businesses an extremely
  reliable and cost effective way to route end users to Internet applications by translating
  names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers
  use to connect to each other. Amazon Route 53 is fully compliant with IPv6 as well.Amazon
  Route 53 effectively connects user requests to infrastructure running in AWS &ndash;
  such as Amazon EC2 instances, Elastic Load Balancing load balancers, or Amazon S3
  buckets &ndash; and can also be used to route users to infrastructure outside of
  AWS. You can use Amazon Route 53 to configure DNS health checks to route traffic
  to healthy endpoints or to independently monitor the health of your application
  and its endpoints. Amazon Route 53 Traffic Flow makes it easy for you to manage
  traffic globally through a variety of routing types, including Latency Based Routing,
  Geo DNS, and Weighted Round Robin&mdash;all of which can be combined with DNS Failover
  in order to enable a variety of low-latency, fault-tolerant architectures. Using
  Amazon Route 53 Traffic Flow&rsquo;s simple visual editor, you can easily manage
  how your end-users are routed to your application&rsquo;s endpoints&mdash;whether
  in a single AWS region or distributed around the globe. Amazon Route 53 also offers
  Domain Name Registration &ndash; you can purchase and manage domain names such as
  example.com and Amazon Route 53 will automatically configure DNS settings for your
  domains.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
x-kinRank: "8"
x-alexaRank: "0"
tags: VPC
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Route 53 API Associate V P C With Hosted Zone
  x-api-slug: aws-route-53-api
  description: Associates an Amazon VPC with a private hosted zone. ImportantTo perform
    the association, the VPC and the private hosted zone must already exist. You can't
    convert a public hosted zone into a private hosted zone.Send a POST request to
    the /2013-04-01/hostedzone/hosted zone ID/associatevpc resource. The request body
    must include a document with an AssociateVPCWithHostedZoneRequest element. The
    response contains a ChangeInfo data type that you can use to track the progress
    of the request. NoteIf you want to associate a VPC that was created by using one
    AWS account with a private hosted zone that was created by using a different account,
    the AWS account that created the private hosted zone must first submit a CreateVPCAssociationAuthorization
    request. Then the account that created the VPC must submit an AssociateVPCWithHostedZone
    request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: ://///2013-04-01/hostedzone/Id/associatevpc
  tags: VPC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneidassociatevpc-post-openapi.md
- name: AWS Route 53 API Create V P C Association Authorization
  x-api-slug: aws-route-53-api
  description: Authorizes the AWS account that created a specified VPC to submit an
    AssociateVPCWithHostedZone request to associate the VPC with a specified hosted
    zone that was created by a different account. To submit a CreateVPCAssociationAuthorization
    request, you must use the account that created the hosted zone. After you authorize
    the association, use the account that created the VPC to submit an AssociateVPCWithHostedZone
    request.NoteIf you want to associate multiple VPCs that you created by using one
    account with a hosted zone that you created by using a different account, you
    must submit one authorization request for each VPC.Send a POST request to the
    /2013-04-01/hostedzone/hosted zone ID/authorizevpcassociation resource. The request
    body must include a document with a CreateVPCAssociationAuthorizationRequest element.
    The response contains information about the authorization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: ://///2013-04-01/hostedzone/Id/authorizevpcassociation
  tags: VPC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneidauthorizevpcassociation-post-openapi.md
- name: AWS Route 53 API Delete V P C Association Authorization
  x-api-slug: aws-route-53-api
  description: Removes authorization to submit an AssociateVPCWithHostedZone request
    to associate a specified VPC with a hosted zone that was created by a different
    account. You must use the account that created the hosted zone to submit a DeleteVPCAssociationAuthorization
    request.ImportantSending this request only prevents the AWS account that created
    the VPC from associating the VPC with the Amazon Route 53 hosted zone in the future.
    If the VPC is already associated with the hosted zone, DeleteVPCAssociationAuthorization
    won't disassociate the VPC from the hosted zone. If you want to delete an existing
    association, use DisassociateVPCFromHostedZone.Send a DELETE request to the /2013-04-01/hostedzone/hosted
    zone ID/deauthorizevpcassociation resource. The request body must include a document
    with a DeleteVPCAssociationAuthorizationRequest element.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: ://///2013-04-01/hostedzone/Id/deauthorizevpcassociation
  tags: VPC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneiddeauthorizevpcassociation-post-openapi.md
- name: AWS Route 53 API Disassociate V P C From Hosted Zone
  x-api-slug: aws-route-53-api
  description: Disassociates a VPC from a Amazon Route 53 private hosted zone. NoteYou
    can't disassociate the last VPC from a private hosted zone.Send a POST request
    to the /2013-04-01/hostedzone/hosted zone ID/disassociatevpcresource. The request
    body must include a document with a DisassociateVPCFromHostedZoneRequest element.
    The response includes a DisassociateVPCFromHostedZoneResponse element.ImportantYou
    can't disassociate a VPC from a private hosted zone when only one VPC is associated
    with the hosted zone. You also can't convert a private hosted zone into a public
    hosted zone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: ://///2013-04-01/hostedzone/Id/disassociatevpc
  tags: VPC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneiddisassociatevpc-post-openapi.md
- name: AWS Route 53 API List V P C Association Authorizations
  x-api-slug: aws-route-53-api
  description: 'Gets a list of the VPCs that were created by other accounts and that
    can be associated with a specified hosted zone because you''ve submitted one or
    more CreateVPCAssociationAuthorization requests. Send a GET request to the /2013-04-01/hostedzone/hosted
    zone ID/authorizevpcassociation resource. The response to this request includes
    a VPCs element with a VPC child element for each VPC that can be associated with
    the hosted zone.Amazon Route 53 returns up to 50 VPCs per page. To return fewer
    VPCs per page, include the MaxResults parameter:             /2013-04-01/hostedzone/hosted
    zone ID/authorizevpcassociation?MaxItems=VPCs per page                     If
    the response includes a NextToken element, there are more VPCs to list. To get
    the next page of VPCs, submit another ListVPCAssociationAuthorizations request,
    and include the value of the NextToken element from the response in the NextToken
    request parameter:            /2013-04-01/hostedzone/hosted zone ID/authorizevpcassociation?MaxItems=VPCs
    per page&amp;NextToken='
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: ://///2013-04-01/hostedzone/Id/authorizevpcassociation&amp;maxresults=MaxResults?nexttoken=NextToken
  tags: VPC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneidauthorizevpcassociationampmaxresultsmaxresultsnexttokennexttoken-get-openapi.md
- name: AWS Route 53 API
  x-api-slug: aws-route-53-api
  description: Amazon Route 53 is a highly available and scalable cloud Domain Name
    System (DNS) web service. It is designed to give developers and businesses an
    extremely reliable and cost effective way to route end users to Internet applications
    by translating names like www.example.com into the numeric IP addresses like 192.0.2.1
    that computers use to connect to each other. Amazon Route 53 is fully compliant
    with IPv6 as well.Amazon Route 53 effectively connects user requests to infrastructure
    running in AWS &ndash; such as Amazon EC2 instances, Elastic Load Balancing load
    balancers, or Amazon S3 buckets &ndash; and can also be used to route users to
    infrastructure outside of AWS. You can use Amazon Route 53 to configure DNS health
    checks to route traffic to healthy endpoints or to independently monitor the health
    of your application and its endpoints. Amazon Route 53 Traffic Flow makes it easy
    for you to manage traffic globally through a variety of routing types, including
    Latency Based Routing, Geo DNS, and Weighted Round Robin&mdash;all of which can
    be combined with DNS Failover in order to enable a variety of low-latency, fault-tolerant
    architectures. Using Amazon Route 53 Traffic Flow&rsquo;s simple visual editor,
    you can easily manage how your end-users are routed to your application&rsquo;s
    endpoints&mdash;whether in a single AWS region or distributed around the globe.
    Amazon Route 53 also offers Domain Name Registration &ndash; you can purchase
    and manage domain names such as example.com and Amazon Route 53 will automatically
    configure DNS settings for your domains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: VPC
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/Route53/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/route53/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=87
- type: x-pricing
  url: https://aws.amazon.com/route53/pricing/
- type: x-registrar-policies
  url: https://aws.amazon.com/route53/amazon-registrar-policies/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-service-level-agreement
  url: https://aws.amazon.com/route53/sla
- type: x-sla
  url: https://aws.amazon.com/route53/sla/
- type: x-website
  url: https://aws.amazon.com/route53/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---