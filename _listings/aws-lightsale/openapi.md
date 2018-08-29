swagger: "2.0"
x-collection-name: AWS Lightsale
x-complete: 1
info:
  title: AWS Lightsale API
  version: 1.0.0
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