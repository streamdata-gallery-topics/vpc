---
name: AWS Lightsale
x-slug: aws-lightsale
description: Amazon Lightsail is the easiest way to get started with AWS for developers
  who just need virtual private servers. Lightsail includes everything you need to
  launch your project quickly - a virtual machine, SSD-based storage, data transfer,
  DNS management, and a static IP - for a low, predictable price. You manage those
  Lightsail servers through the Lightsail console or by using the API or command-line
  interface (CLI).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
x-kinRank: "10"
x-alexaRank: "0"
tags: VPC
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-lightsale/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Lightsale API - Is Vpc Peered
  x-api-slug: actionisvpcpeered-get
  description: Returns a Boolean value indicating whether your Lightsail VPC is peered.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: :///
  tags: Amazon Web Services, DNS, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-lightsale/actionisvpcpeered-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-lightsale/actionisvpcpeered-get-openapi.md
- name: AWS Lightsale API - Peer Vpc
  x-api-slug: actionpeervpc-get
  description: Tries to peer the Lightsail VPC with the user's default VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: :///
  tags: Amazon Web Services, DNS, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-lightsale/actionpeervpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-lightsale/actionpeervpc-get-openapi.md
- name: AWS Lightsale API - Unpeer Vpc
  x-api-slug: actionunpeervpc-get
  description: Attempts to unpeer the Lightsail VPC from the user's default VPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-lightsail.png
  humanURL: https://amazonlightsail.com/
  baseURL: :///
  tags: Amazon Web Services, DNS, Stack Network, API Service Provider, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-lightsale/actionunpeervpc-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/vpc/master/_listings/aws-lightsale/actionunpeervpc-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.lambda.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.lightsale.stack.network
- type: x-documentation
  url: https://docs.aws.amazon.com/lightsail/2016-11-28/api-reference/Welcome.html?fid=6DDA37DF97F08F8B-23761D4A79F7B1E
- type: x-pricing
  url: https://amazonlightsail.com/pricing/
- type: x-website
  url: https://amazonlightsail.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---