---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Border
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Get Range Border
  x-api-slug: microsoft-graph
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph Get Range Border
  x-api-slug: microsoft-graph
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders(&lt;sideIndex&gt;)
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph Get Range Border
  x-api-slug: microsoft-graph
  description: Get RangeBorder Retrieve the properties and relationships of rangeborder
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-get-openapi.md
- name: Microsoft Graph List Range Border Collection
  x-api-slug: microsoft-graph
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders
  tags: List, Range, Border, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-get-openapi.md
- name: Microsoft Graph List Range Border Collection
  x-api-slug: microsoft-graph
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders
  tags: List, Range, Border, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-get-openapi.md
- name: Microsoft Graph List Range Border Collection
  x-api-slug: microsoft-graph
  description: List RangeBorderCollection Retrieve a list of rangeborder objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders
  tags: List, Range, Border, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-get-openapi.md
- name: Microsoft Graph Update Rangeborder
  x-api-slug: microsoft-graph
  description: Update rangeborder Update the properties of rangeborder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Rangeborder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersltsideindexgt-patch-openapi.md
- name: Microsoft Graph Update Rangeborder
  x-api-slug: microsoft-graph
  description: Update rangeborder Update the properties of rangeborder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders(&lt;sideIndex&gt;)
  tags: Rangeborder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersltsideindexgt-patch-openapi.md
- name: Microsoft Graph Update Rangeborder
  x-api-slug: microsoft-graph
  description: Update rangeborder Update the properties of rangeborder object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders(&lt;sideIndex&gt;)
  tags: Rangeborder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersltsideindexgt-patch-openapi.md
- name: Microsoft Graph Range Border Collection Item At
  x-api-slug: microsoft-graph
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders/ItemAt
  tags: Range, Border, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatbordersitemat-post-openapi.md
- name: Microsoft Graph Range Border Collection Item At
  x-api-slug: microsoft-graph
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders/ItemAt
  tags: Range, Border, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatbordersitemat-post-openapi.md
- name: Microsoft Graph Range Border Collection Item At
  x-api-slug: microsoft-graph
  description: 'RangeBorderCollection: ItemAt Gets a border object using its index'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders/ItemAt
  tags: Range, Border, Collection, Item, At
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatbordersitemat-post-openapi.md
- name: Microsoft Graph Create Range Border
  x-api-slug: microsoft-graph
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/borders
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatborders-post-openapi.md
- name: Microsoft Graph Create Range Border
  x-api-slug: microsoft-graph
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/borders
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatborders-post-openapi.md
- name: Microsoft Graph Create Range Border
  x-api-slug: microsoft-graph
  description: Create RangeBorder Use this API to create a new RangeBorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/borders
  tags: Range, Border
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatborders-post-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Border
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/border/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---