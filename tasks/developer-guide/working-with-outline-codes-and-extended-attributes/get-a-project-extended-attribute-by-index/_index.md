---
title: "Get A Project Extended Attribute by Index"
type: docs
url: /get-a-project-extended-attribute-by-index/
weight: 60
---

## **Introduction**
This example allows you to retrieve project extended attribute definition using Aspose.Tasks Cloud API in your applications. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/extendedAttributes/{index}|GET|Read extended attribute information from a MS Project File|[GetExtendedAttributeByIndex](https://apireference.aspose.cloud/tasks/#/TasksExtendedAttributes/GetExtendedAttributeByIndex)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

url -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/extendedAttributes/1" -H "accept: application/json" 

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "extendedAttribute": {
    "fieldId": "string",
    "fieldName": "string",
    "cfType": "Null",
    "guid": "string",
    "elementType": "Null",
    "maxMultiValues": 0,
    "userDef": true,
    "alias": "string",
    "secondaryPid": "string",
    "autoRollDown": true,
    "defaultGuid": "string",
    "lookupUid": "string",
    "phoneticsAlias": "string",
    "rollupType": "Null",
    "calculationType": "None",
    "formula": "string",
    "restrictValues": true,
    "valuelistSortOrder": 0,
    "appendNewValues": true,
    "default": "string",
    "valueList": [
      {
        "id": 0,
        "val": "string",
        "dateTimeValue": "2020-09-19T10:34:31.421Z",
        "durationValue": 0,
        "description": "string",
        "phonetic": "string"
      }
    ],
    "secondaryGuid": "string"
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-GetExtendedAttributeDefination-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getExtendedAttributeByIndex.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "9b3aa54500fb7427a11c3983bde7552a" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "e05c60646254afcf20cccfaa5618ae85" >}}

{{< /tab >}}

{{< /tabs >}}
