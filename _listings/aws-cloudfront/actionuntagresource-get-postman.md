{
  "info": {
    "name": "AWS CloudFront API Untag Resource",
    "_postman_id": "74841ab7-ffc7-4fb3-8fbe-396171269846",
    "description": "Remove tags from a CloudFront resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cloud",
      "item": [
        {
          "id": "be12893f-5550-45cd-8eb5-b00b1067bae1",
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
              "id": "27444d0f-2625-4445-a90e-7f374069fb45"
            }
          ]
        },
        {
          "id": "9ef4b626-445d-4b95-9b40-572ca61b2360",
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
              "id": "ab76dd15-9b91-491f-a7f4-34423efb83ba"
            }
          ]
        },
        {
          "id": "b35173f0-7c7d-466a-8ad9-dfa43fd876aa",
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
              "id": "f9faaff0-e394-4a6c-819d-005c2ed7a66f"
            }
          ]
        },
        {
          "id": "d7cb0f1a-0bf7-4e7a-aebb-939bf3fb3980",
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
              "id": "c3be87f2-fabc-4208-9c07-88b94f0ba5ff"
            }
          ]
        }
      ]
    },
    {
      "name": "Distribution",
      "item": [
        {
          "id": "0ed9bc09-4536-43be-8aaf-3a1d1de02b79",
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
              "id": "e09a8134-cdaa-445e-b618-c8b2ad7ccc1e"
            }
          ]
        },
        {
          "id": "bdd09cab-7c47-43eb-9016-73a55b0abf58",
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
              "id": "68c15c3a-8c91-40cb-913a-0469d0e57569"
            }
          ]
        },
        {
          "id": "b21a3d0c-6bc4-4d00-a030-3c2315a13573",
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
              "id": "0c6e213b-51d3-4d0f-a3b8-d21817dc9521"
            }
          ]
        },
        {
          "id": "df07c2bd-6ffe-446c-b292-6c1897c217c3",
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
              "id": "6c053198-f719-48c0-b0cb-28be02b4393b"
            }
          ]
        },
        {
          "id": "a4bc766b-9a27-4a45-941d-9144f94fd334",
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
              "id": "57570827-a7f0-48bd-9363-017bbc6cd236"
            }
          ]
        }
      ]
    },
    {
      "name": "Invalidation",
      "item": [
        {
          "id": "68962ac6-bae8-44b2-86b3-5f13d364b0e3",
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
              "id": "8702c7c2-33eb-46d8-b441-e22f0065fdde"
            }
          ]
        },
        {
          "id": "3baed81f-681f-4a13-9f0a-dfd8c7d82036",
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
              "id": "f50df758-8310-4030-8972-a1282a60cdab"
            }
          ]
        }
      ]
    },
    {
      "name": "Streaming",
      "item": [
        {
          "id": "fe4b8bb5-749f-4fa8-b946-f5e9e80567e3",
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
              "id": "b388e282-7f4d-46d4-a5d4-d85e91d40952"
            }
          ]
        },
        {
          "id": "d76b0a77-3c86-4e18-9563-ced002277257",
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
              "id": "598a0544-3ba3-49fd-9eb8-d73b26ef907a"
            }
          ]
        },
        {
          "id": "7c36c74b-e9cf-49f6-8d71-cbc892ee5b43",
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
              "id": "7db9171a-242d-4bc0-ac56-19717345ea09"
            }
          ]
        },
        {
          "id": "14e3a1f3-c8fa-4b49-a93a-a2caa370e0a0",
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
              "id": "c30732d5-df1f-4226-8e44-5588047b7bd9"
            }
          ]
        },
        {
          "id": "1686b9a5-982c-491c-b20d-c5cabf7810d5",
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
              "id": "9f298cc2-2e1f-4294-ad30-9859aa569f95"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "3e0bf4bf-7691-4c52-8f24-0e26511ab01c",
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
              "id": "e95279ec-1783-4415-97f0-13182daaf22a"
            }
          ]
        },
        {
          "id": "d54c474e-494c-49d8-b853-8130207f6282",
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
              "id": "8b0ceb53-b582-4b02-988c-8ee0aba1735a"
            }
          ]
        },
        {
          "id": "0deac418-af88-43fa-8572-13ea7df80f1d",
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
              "id": "dcbb65e4-acd3-44bf-b800-414a9a513a54"
            }
          ]
        },
        {
          "id": "c3ec14a7-9a41-4a3d-88e5-e7d6f1a584bc",
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
              "id": "f73563a9-da1a-40ee-81ca-b042943675dc"
            }
          ]
        },
        {
          "id": "e1031a26-2515-4c82-aeda-512a4dbe6218",
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
              "id": "fc62d22a-fd6b-4750-8bc1-66e6927ac322"
            }
          ]
        },
        {
          "id": "26fe7710-3f81-4d73-95c5-2e3a0688472e",
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
              "id": "9fc271f2-264e-4bb8-8bcf-d27affba659a"
            }
          ]
        }
      ]
    },
    {
      "name": "Tag",
      "item": [
        {
          "id": "586dc200-5f0e-48e7-ab16-4f449d90a215",
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
              "id": "bc4d0e24-42d6-40d7-a06e-1c837d2c673b"
            }
          ]
        }
      ]
    },
    {
      "name": "Untag",
      "item": [
        {
          "id": "5eea6039-984e-409c-a62f-35b00d4ca945",
          "name": "untagResource",
          "request": {
            "url": "http://example.com/api/?Action=UntagResource?Device=Device&DryRun=DryRun&InstanceId=InstanceId&Resource=Resource&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Remove tags from a CloudFront resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c646d6b4-cff3-481e-9966-5e2402a2ee3f"
            }
          ]
        }
      ]
    }
  ]
}