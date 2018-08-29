---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Revoke D B Security Group Ingress
  version: 1.0.0
  description: Revokes ingress from a DBSecurityGroup for previously authorized IP
    ranges or EC2 or VPC Security Groups.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=RevokeDBSecurityGroupIngress:
    get:
      summary: Revoke D B Security Group Ingress
      description: Revokes ingress from a DBSecurityGroup for previously authorized
        IP ranges or EC2 or VPC Security Groups.
      operationId: revokedbsecuritygroupingress
      x-api-path-slug: actionrevokedbsecuritygroupingress-get
      parameters:
      - in: query
        name: CIDRIP
        description: The IP range to revoke access from
        type: string
      - in: query
        name: DBSecurityGroupName
        description: The name of the DB security group to revoke ingress from
        type: string
      - in: query
        name: EC2SecurityGroupId
        description: The id of the EC2 security group to revoke access from
        type: string
      - in: query
        name: EC2SecurityGroupName
        description: The name of the EC2 security group to revoke access from
        type: string
      - in: query
        name: EC2SecurityGroupOwnerId
        description: The AWS Account Number of the owner of the EC2 security group        specified
          in the EC2SecurityGroupName parameter
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security Groups
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