---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Attach Classic Link Vpc
  version: 1.0.0
  description: "Links an EC2-Classic instance to a ClassicLink-enabled VPC through
    one or more of the VPC's\n\t\t\tsecurity groups."
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
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