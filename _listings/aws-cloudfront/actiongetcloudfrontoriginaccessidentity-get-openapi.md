---
swagger: "2.0"
x-collection-name: AWS CloudFront
x-complete: 0
info:
  title: AWS CloudFront API Get Cloud Front Origin Access Identity
  version: 1.0.0
  description: Get the information about an origin access identity.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateCloudFrontOriginAccessIdentity:
    get:
      summary: Create Cloud Front Origin Access Identity
      description: Creates a new origin access identity.
      operationId: createCloudFrontOriginAccessIdentity
      x-api-path-slug: actioncreatecloudfrontoriginaccessidentity-get
      parameters:
      - in: query
        name: CloudFrontOriginAccessIdentityConfig
        description: The current configuration information for the identity
        type: string
      - in: query
        name: CreateCloudFrontOriginAccessIdentityRequest
        description: Root level tag for the CreateCloudFrontOriginAccessIdentityRequest
          parameters
        type: string
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
        name: VpcId.N
        description: One or more VPCs for which you want to describe the ClassicLink
          status
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloud
      - Front
      - Origin
      - Access
      - Identity
  /?Action=DeleteCloudFrontOriginAccessIdentity:
    get:
      summary: Delete Cloud Front Origin Access Identity
      description: Delete an origin access identity.
      operationId: deleteCloudFrontOriginAccessIdentity
      x-api-path-slug: actiondeletecloudfrontoriginaccessidentity-get
      parameters:
      - in: query
        name: Id
        description: The origin access identitys ID
        type: string
      - in: query
        name: If-Match
        description: The value of the ETag header you received from a previous GET      or
          PUT request
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloud
      - Front
      - Origin
      - Access
      - Identity
  /?Action=GetCloudFrontOriginAccessIdentity:
    get:
      summary: Get Cloud Front Origin Access Identity
      description: Get the information about an origin access identity.
      operationId: getCloudFrontOriginAccessIdentity
      x-api-path-slug: actiongetcloudfrontoriginaccessidentity-get
      parameters:
      - in: query
        name: CustomerGatewayId.N
        description: One or more customer gateway IDs
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: Id
        description: The identitys ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloud
      - Front
      - Origin
      - Access
      - Identity
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