---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Enable Vpc Classic Link
  version: 1.0.0
  description: Enables a VPC for ClassicLink.
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