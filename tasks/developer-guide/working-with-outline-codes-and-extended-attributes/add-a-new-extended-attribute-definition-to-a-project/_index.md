---
title: "Add a new Extended Attribute definition to a Project"
type: docs
url: /add-a-new-extended-attribute-definition-to-a-project/
weight: 80
---

## **Introduction**
This example allows you to add a new extended attribute in a project using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/extendedAttributes|PUT|Add a new extended attribute definition to a project or updates existing attribute definition|[PutExtendedAttribute](https://apireference.aspose.cloud/tasks/#/TasksExtendedAttributes/PutExtendedAttribute)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/NewProductDev.mpp/extendedAttributes" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "{ \"fieldId\": \"string\", \"fieldName\": \"Text3\", \"cfType\": \"Text\", \"guid\": \"string\", \"elementType\": \"Task\", \"maxMultiValues\": 0, \"userDef\": true, \"alias\": \"New Field\", \"secondaryPid\": \"string\", \"autoRollDown\": true, \"defaultGuid\": \"string\", \"lookupUid\": \"string\", \"phoneticsAlias\": \"string\", \"rollupType\": \"Null\", \"calculationType\": \"Lookup\", \"formula\": \"string\", \"restrictValues\": true, \"valuelistSortOrder\": 0, \"appendNewValues\": true, \"default\": \"string\", \"valueList\": [ { \"id\": 111, \"val\": \"Internal\", \"dateTimeValue\": \"2020-09-19T10:38:41.713Z\", \"durationValue\": 0, \"description\": \"descr1\", \"phonetic\": \"string\" }, { \"id\": 112, \"val\": \"External\", \"dateTimeValue\": \"2020-09-19T10:38:41.713Z\", \"durationValue\": 0, \"description\": \"descr2\", \"phonetic\": \"string\" } ], \"secondaryGuid\": \"string\"}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "extendedAttribute": {
    "link": {
      "href": "string",
      "rel": "string",
      "type": "string",
      "title": "string"
    },
    "index": 0,
    "fieldName": "string",
    "alias": "string",
    "fieldId": "string"
  }
}
```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-PutExtendedAttribute.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "cb8264639fd09956a01ded367242cafc" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "b979306c391c8d3599c2b95d367452d1" >}}

{{< /tab >}}

{{< /tabs >}}
