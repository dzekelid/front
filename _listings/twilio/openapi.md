swagger: "2.0"
x-collection-name: Twilio
x-complete: 1
info:
  title: Twilio
  description: twilio-is-a-cloud-communications-infrastructure-as-a-serviceiaas-company-based-in-san-francisco-california--twilio-allows-software-developers-to-programmatically-make-and-receive-phone-calls-and-send-and-receive-text-messages-using-its-web-service-apis--twilios-services-are-accessed-over-http-and-are-billed-based-on-usage-
  termsOfService: https://www.twilio.com/legal/tos
  version: v1
host: api.twilio.com
basePath: /2010-04-01/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Accounts/{AccountSid}/Queues/{QueueSid}/Members/Front:
    get:
      summary: Get Queue Members In Front
      description: Get a front member.
      operationId: get-a-front-member
      x-api-path-slug: accountsaccountsidqueuesqueuesidmembersfront-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
    post:
      summary: Update Queue Members In Front
      description: Posting a URL and Method to a Queue instance will dequeue a member
        from anqueue and have the members call begin executing the TwiML document
        at that URLnWhen dequeuing the Front of the queue, the next call in the queue
        will be redirected.n
      operationId: posting-a-url-and-method-to-a-queue-instance-will-dequeue-a-member-from-aqueue-and-have-the-members-
      x-api-path-slug: accountsaccountsidqueuesqueuesidmembersfront-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues