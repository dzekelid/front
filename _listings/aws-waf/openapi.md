swagger: "2.0"
x-collection-name: AWS WAF
x-complete: 1
info:
  title: AWS WAF API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateWebACL:
    get:
      summary: Create Web ACL
      description: 'Service: AWS WAFCreates a WebACL, which contains the Rules that
        identify the CloudFront web requests that you want to allow, block, or count.'
      operationId: createWebACL
      x-api-path-slug: actioncreatewebacl-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: DefaultAction
        description: The action that you want  AWS WAF to take when a request doesnt
          match the criteria specified in any of the Rule objects that are associated
          with the WebACL
        type: string
      - in: query
        name: MetricName
        description: A friendly name or description for the metrics for this WebACL
        type: string
      - in: query
        name: Name
        description: A friendly name or description of the WebACL
        type: string
      responses:
        200:
          description: OK
      tags:
      - Web ACL