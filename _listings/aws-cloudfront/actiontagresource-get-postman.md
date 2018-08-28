{
  "info": {
    "name": "AWS CloudFront API Tag Resource",
    "_postman_id": "bf2250cb-c94f-432f-8ada-da117084e7fa",
    "description": "Add tags to a CloudFront resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cloud",
      "item": [
        {
          "id": "221ec5b1-72d7-4fd3-b9d2-4775d675c431",
          "name": "createCloudFrontOriginAccessIdentity",
          "request": {
            "url": "http://example.com/api/?Action=CreateCloudFrontOriginAccessIdentity?CloudFrontOriginAccessIdentityConfig=CloudFrontOriginAccessIdentityConfig&CreateCloudFrontOriginAccessIdentityRequest=CreateCloudFrontOriginAccessIdentityRequest&DryRun=DryRun&Filter.N=Filter.N&VpcId.N=VpcId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new origin access identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68884b0b-77ef-48a0-9946-4b5e26b44735"
            }
          ]
        },
        {
          "id": "78a02318-4a8f-4878-8a2b-86376d2e7d64",
          "name": "deleteCloudFrontOriginAccessIdentity",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCloudFrontOriginAccessIdentity?Id=Id&If-Match=If-Match&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an origin access identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0968684d-c38a-4441-ae65-03d2499ede67"
            }
          ]
        },
        {
          "id": "686b56ab-5a37-44c5-8fe0-8c0519159f6b",
          "name": "getCloudFrontOriginAccessIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetCloudFrontOriginAccessIdentity?CustomerGatewayId.N=CustomerGatewayId.N&DryRun=DryRun&Filter.N=Filter.N&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the information about an origin access identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b15f9b8-7989-43c1-9499-0d85714cddc8"
            }
          ]
        },
        {
          "id": "83c13bb1-2679-4272-ac18-1c4342419acb",
          "name": "getCloudFrontOriginAccessIdentityConfig",
          "request": {
            "url": "http://example.com/api/?Action=GetCloudFrontOriginAccessIdentityConfig?AutoPlacement=AutoPlacement&AvailabilityZone=AvailabilityZone&ClientToken=ClientToken&Id=Id&InstanceType=InstanceType&Quantity=Quantity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the configuration information about an origin access identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f5241af-f057-4ef0-9672-889b60446891"
            }
          ]
        }
      ]
    },
    {
      "name": "Distribution",
      "item": [
        {
          "id": "524ec2aa-e520-4902-a15b-ec521a6818c9",
          "name": "createDistribution",
          "request": {
            "url": "http://example.com/api/?Action=CreateDistribution?CreateDistributionRequest=CreateDistributionRequest&DistributionConfig=DistributionConfig&MaxResults=MaxResults&NextToken=NextToken&VpcIds.N=VpcIds.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new web distribution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0994b11e-ed86-4e56-91d9-84ab6067839b"
            }
          ]
        },
        {
          "id": "79c9eccc-9050-47ca-a2a1-3aa9efa50f3f",
          "name": "createDistributionWithTags",
          "request": {
            "url": "http://example.com/api/?Action=CreateDistributionWithTags?CreateDistributionWithTagsRequest=CreateDistributionWithTagsRequest&DistributionConfigWithTags=DistributionConfigWithTags&DryRun=DryRun&InstanceId=InstanceId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new distribution with tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f14004a5-aac8-419f-8938-2e088545fe6c"
            }
          ]
        },
        {
          "id": "4497964f-94dd-42ea-a7c4-175dab3f3cb7",
          "name": "deleteDistribution",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDistribution?BgpAsn=BgpAsn&DryRun=DryRun&Id=Id&If-Match=If-Match&IpAddress=IpAddress&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a distribution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1aca119e-f5eb-4107-956f-679564b456d9"
            }
          ]
        },
        {
          "id": "89a3174e-204e-44a4-9d56-34e3dba6a150",
          "name": "getDistribution",
          "request": {
            "url": "http://example.com/api/?Action=GetDistribution?Filter.N=Filter.N&HostId.N=HostId.N&Id=Id&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the information about a distribution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9cb1b9c-a765-46c0-92eb-03d74edbd870"
            }
          ]
        },
        {
          "id": "ce3234eb-cd7b-4ab2-8bf5-fc74245e4173",
          "name": "getDistributionConfig",
          "request": {
            "url": "http://example.com/api/?Action=GetDistributionConfig?Filter.N=Filter.N&Id=Id&MaxDuration=MaxDuration&MaxResults=MaxResults&MinDuration=MinDuration&NextToken=NextToken&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the configuration information about a distribution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2f3f5db-e4e0-438c-a007-3a8603324836"
            }
          ]
        }
      ]
    },
    {
      "name": "Invalidation",
      "item": [
        {
          "id": "1abf5a69-a912-4ac1-9dcf-a13c9ed20c4f",
          "name": "createInvalidation",
          "request": {
            "url": "http://example.com/api/?Action=CreateInvalidation?DistributionId=DistributionId&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new invalidation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85333bbe-2eee-4c3c-9f43-38217b2604f4"
            }
          ]
        },
        {
          "id": "3be65ac7-afad-45f6-b705-2761c41b04be",
          "name": "getInvalidation",
          "request": {
            "url": "http://example.com/api/?Action=GetInvalidation?DistributionId=DistributionId&Filter.N=Filter.N&HostReservationIdSet.N=HostReservationIdSet.N&Id=Id&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the information about an invalidation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f738b974-5bb8-462f-988f-ffa9cf97911a"
            }
          ]
        }
      ]
    },
    {
      "name": "Streaming",
      "item": [
        {
          "id": "1404d165-d186-4fca-9210-21aa8d26fa1e",
          "name": "createStreamingDistribution",
          "request": {
            "url": "http://example.com/api/?Action=CreateStreamingDistribution?CreateStreamingDistributionRequest=CreateStreamingDistributionRequest&StreamingDistributionConfig=StreamingDistributionConfig&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new RMTP distribution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab952321-7782-474b-97fe-ffd88afdce09"
            }
          ]
        },
        {
          "id": "98bbae81-fb0f-4d32-bda3-882277309df2",
          "name": "createStreamingDistributionWithTags",
          "request": {
            "url": "http://example.com/api/?Action=CreateStreamingDistributionWithTags?CreateStreamingDistributionWithTagsRequest=CreateStreamingDistributionWithTagsRequest&DryRun=DryRun&StreamingDistributionConfigWithTags=StreamingDistributionConfigWithTags&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create a new streaming distribution with tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4aae206-99ac-430a-9fa6-d2bd66346fc2"
            }
          ]
        },
        {
          "id": "2b0f6310-c81b-4da2-bd32-71d97681d793",
          "name": "deleteStreamingDistribution",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStreamingDistribution?CustomerGatewayId=CustomerGatewayId&DryRun=DryRun&Id=Id&If-Match=If-Match",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a streaming distribution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe5c9320-3c13-4d72-8f0b-74c4ce8ef3db"
            }
          ]
        },
        {
          "id": "52947860-8ce1-42a4-bb21-6327a0fd725b",
          "name": "getStreamingDistribution",
          "request": {
            "url": "http://example.com/api/?Action=GetStreamingDistribution?HostIdSet.N=HostIdSet.N&Id=Id&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets information about a specified RTMP distribution, including the distribution\n      configuration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53a915ed-cf17-4432-baa6-0156a1f5bd8d"
            }
          ]
        },
        {
          "id": "43cc6b3c-f575-44c9-ab21-4384228b7b12",
          "name": "getStreamingDistributionConfig",
          "request": {
            "url": "http://example.com/api/?Action=GetStreamingDistributionConfig?AutoPlacement=AutoPlacement&HostId.N=HostId.N&Id=Id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the configuration information about a streaming distribution."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36ce5aef-df31-45f0-8b26-46a8756da3bd"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "e8602338-8f3d-4e5f-8164-2443da5de88f",
          "name": "listCloudFrontOriginAccessIdentities",
          "request": {
            "url": "http://example.com/api/?Action=ListCloudFrontOriginAccessIdentities?Affinity=Affinity&HostId=HostId&InstanceId=InstanceId&Marker=Marker&MaxItems=MaxItems&Tenancy=Tenancy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists origin access identities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c60543e3-8b70-4b97-8adf-1cb9dffdd79f"
            }
          ]
        },
        {
          "id": "d4c36e8b-aae9-40be-9f3e-e575fabf6e23",
          "name": "listDistributions",
          "request": {
            "url": "http://example.com/api/?Action=ListDistributions?ClientToken=ClientToken&CurrencyCode=CurrencyCode&HostIdSet.N=HostIdSet.N&LimitPrice=LimitPrice&Marker=Marker&MaxItems=MaxItems&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List distributions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51f4173d-f7b4-4f94-b802-8b6758cfc1f8"
            }
          ]
        },
        {
          "id": "b47cdec8-77e7-4470-81a0-612cf41f81b5",
          "name": "listDistributionsByWebACLId",
          "request": {
            "url": "http://example.com/api/?Action=ListDistributionsByWebACLId?HostId.N=HostId.N&Marker=Marker&MaxItems=MaxItems&WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the distributions that are associated with a specified AWS WAF web ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "222c67f5-6c8b-4e0a-bd19-4c14f71256bf"
            }
          ]
        },
        {
          "id": "c1c52aeb-d607-4833-b8ee-c951382fa217",
          "name": "listInvalidations",
          "request": {
            "url": "http://example.com/api/?Action=ListInvalidations?DhcpOptionsId=DhcpOptionsId&DistributionId=DistributionId&DryRun=DryRun&Marker=Marker&MaxItems=MaxItems&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists invalidation batches."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d878c05-ec70-450b-85a0-01df8369ad13"
            }
          ]
        },
        {
          "id": "2ab37a3c-4603-426d-b72c-27ab4e353998",
          "name": "listStreamingDistributions",
          "request": {
            "url": "http://example.com/api/?Action=ListStreamingDistributions?DhcpConfiguration.N=DhcpConfiguration.N&DryRun=DryRun&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List streaming distributions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "55368078-c406-4cf8-b489-ed5005d68c72"
            }
          ]
        },
        {
          "id": "b80b0b0d-8191-44c8-a32b-0e382951bf70",
          "name": "listTagsForResource",
          "request": {
            "url": "http://example.com/api/?Action=ListTagsForResource?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun&Resource=Resource",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List tags for a CloudFront resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57edd17b-60b7-4a4b-a0dc-203731528b54"
            }
          ]
        }
      ]
    },
    {
      "name": "Tag",
      "item": [
        {
          "id": "3d6344b9-58a9-4e88-9346-906b0c33e4d5",
          "name": "tagResource",
          "request": {
            "url": "http://example.com/api/?Action=TagResource?DhcpOptionsId.N=DhcpOptionsId.N&DryRun=DryRun&Filter.N=Filter.N&Resource=Resource",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add tags to a CloudFront resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b675cb23-ea32-4638-b5a6-9fd132f0c768"
            }
          ]
        }
      ]
    }
  ]
}