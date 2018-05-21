---
name: Akamai
x-slug: akamai
description: Akamai Technologies, Inc. is a content delivery network or CDN and cloud
  services provider headquartered in Cambridge, Massachusetts, in the United States.
  Akamais content delivery network is one of the worlds largest distributed computing
  platforms, responsible for serving between 15 and 30 percent of all web traffic.
  The company operates a network of servers around the world and rents capacity on
  these servers to customers who want their websites to work faster by distributing
  content from locations close to the user
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Latest
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/akamai/apis.md
specificationVersion: "0.14"
apis:
- name: Akamai API Get a Property&#8217;s Latest Version
  x-api-slug: akamai-api
  description: Get a Property&#8217;s Latest Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions/latest
  tags: Papi, V0, Properties, Property, Versions, Latest, Contract,group,activatedon
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/akamai/papiv0propertiespropertyidversionslatest-get-openapi.md
- name: Akamai API List Test Configurations
  x-api-slug: akamai-api
  description: List Test Configurations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests
  tags: Sla, Tests, Slatests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/akamai/slaapiv1tests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/akamai/slaapiv1tests-get-openapi.md
- name: Akamai API List Performance Reports
  x-api-slug: akamai-api
  description: List Performance Reports
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests/{slaTestId}/reports/performance
  tags: Sla, Tests, Slatest, Reports, Performance, Start,end
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/akamai/slaapiv1testsslatestidreportsperformance-get-openapi.md
- name: Akamai API List Availability Reports
  x-api-slug: akamai-api
  description: List Availability Reports
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests/{slaTestId}/reports/availability
  tags: Sla, Tests, Slatest, Reports, Availability, Start,end
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/akamai/slaapiv1testsslatestidreportsavailability-get-openapi.md
- name: Akamai API
  x-api-slug: akamai-api
  description: Akamai Technologies, Inc. is a content delivery network or CDN and
    cloud services provider headquartered in Cambridge, Massachusetts, in the United
    States. Akamais content delivery network is one of the worlds largest distributed
    computing platforms, responsible for serving between 15 and 30 percent of all
    web traffic. The company operates a network of servers around the world and rents
    capacity on these servers to customers who want their websites to work faster
    by distributing content from locations close to the user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com//
  tags: Latest
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/latest/master/_listings/akamai/openapi.md
x-common:
- type: x-base
  url: https://api.ccu.akamai.com
- type: x-blog
  url: https://blogs.akamai.com
- type: x-blog-rss
  url: http://blogs.akamai.com/feeds.html
- type: x-crunchbase
  url: http://www.crunchbase.com/company/akamai-technologies
- type: x-developer
  url: https://developer.akamai.com/
- type: x-email
  url: open-developer@akamai.com
- type: x-github
  url: https://github.com/akamai
- type: x-twitter
  url: https://twitter.com/Akamai
- type: x-website
  url: https://akamai.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---