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
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Route 53 API - Associate V P C With Hosted Zone
  x-api-slug: 20130401hostedzoneidassociatevpc-post
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
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneidassociatevpc-post-openapi.md
- name: AWS Route 53 API - Create V P C Association Authorization
  x-api-slug: 20130401hostedzoneidauthorizevpcassociation-post
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
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneidauthorizevpcassociation-post-openapi.md
- name: AWS Route 53 API - Delete V P C Association Authorization
  x-api-slug: 20130401hostedzoneiddeauthorizevpcassociation-post
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
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneiddeauthorizevpcassociation-post-openapi.md
- name: AWS Route 53 API - Disassociate V P C From Hosted Zone
  x-api-slug: 20130401hostedzoneiddisassociatevpc-post
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
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneiddisassociatevpc-post-openapi.md
- name: AWS Route 53 API - List V P C Association Authorizations
  x-api-slug: 20130401hostedzoneidauthorizevpcassociationampmaxresultsmaxresultsnexttokennexttoken-get
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
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401hostedzoneidauthorizevpcassociationampmaxresultsmaxresultsnexttokennexttoken-get-openapi.md
- name: AWS Route 53 API - Create Health Check
  x-api-slug: 20130401healthcheck-post
  description: Creates a new health check.To create a new health check, send a POST
    request to the/2013-04-01/healthcheck resource. The request body must include
    a documentwith a CreateHealthCheckRequest element. The response returns theCreateHealthCheckResponse
    element, containing the health check ID specifiedwhen adding health check to a
    resource record set. For information about adding health checksto resource record
    sets, see ResourceRecordSet:HealthCheckId in ChangeResourceRecordSets. If you
    are registering EC2 instances with an Elastic Load Balancing (ELB) loadbalancer,
    do not create Amazon Route 53 health checks for the EC2 instances. When you register
    anEC2 instance with a load balancer, you configure settings for an ELB health
    check, whichperforms a similar function to an Amazon Route 53 health check.You
    can associate health checks with failover resource record sets in a private hostedzone.
    Note the following:Amazon Route 53 health checkers are outside the VPC. To check
    the health of an endpointwithin a VPC by IP address, you must assign a public
    IP address to the instance in theVPC.You can configure a health checker to check
    the health of an external resource thatthe instance relies on, such as a database
    server.You can create a CloudWatch metric, associate an alarm with the metric,
    and then create ahealth check that is based on the state of the alarm. For example,
    you might create a CloudWatchmetric that checks the status of the Amazon EC2 StatusCheckFailed
    metric, add analarm to the metric, and then create a health check that is based
    on the state of thealarm. For information about creating CloudWatch metrics and
    alarms by using the CloudWatch console,see the Amazon CloudWatch User Guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-route-53/20130401healthcheck-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.rekognition.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.route.53.stack.network
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