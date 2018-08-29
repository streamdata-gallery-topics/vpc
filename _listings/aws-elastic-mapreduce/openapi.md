swagger: "2.0"
x-collection-name: AWS Elastic MapReduce
x-complete: 1
info:
  title: AWS Elastic MapReduce API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeCluster:
    get:
      summary: Describe Cluster
      description: Provides cluster-level details including status, hardware and software
        configuration, VPC settings, and so on.
      operationId: describeCluster
      x-api-path-slug: actiondescribecluster-get
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clusters