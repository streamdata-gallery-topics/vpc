---
swagger: "2.0"
x-collection-name: AWS Lightsale
x-complete: 0
info:
  title: Amazon Lightsale API Unpeer Vpc
  version: 1.0.0
  description: Attempts to unpeer the Lightsail VPC from the user's default VPC.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=IsVpcPeered:
    get:
      summary: Is Vpc Peered
      description: Returns a Boolean value indicating whether your Lightsail VPC is
        peered.
      operationId: isVpcPeered
      x-api-path-slug: actionisvpcpeered-get
      parameters:
      - in: query
        name: isPeered
        description: Returns true if the Lightsail VPC is peered; otherwise,      false
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=PeerVpc:
    get:
      summary: Peer Vpc
      description: Tries to peer the Lightsail VPC with the user's default VPC.
      operationId: peerVpc
      x-api-path-slug: actionpeervpc-get
      parameters:
      - in: query
        name: operation
        description: An array of key-value pairs containing information about the
          request      operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=UnpeerVpc:
    get:
      summary: Unpeer Vpc
      description: Attempts to unpeer the Lightsail VPC from the user's default VPC.
      operationId: unpeerVpc
      x-api-path-slug: actionunpeervpc-get
      parameters:
      - in: query
        name: operation
        description: An array of key-value pairs containing information about the
          request      operation
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