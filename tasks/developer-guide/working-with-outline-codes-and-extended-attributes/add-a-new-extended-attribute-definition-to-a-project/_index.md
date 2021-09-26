---
title: "Add a new Extended Attribute definition to a Project"
description: "Aspose.Tasks Cloud allows you to add a new extended attribute definition to a project in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
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
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutExtendedAttribute.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putExtendedAttribute.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "cb8264639fd09956a01ded367242cafc" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "b979306c391c8d3599c2b95d367452d1" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutExtendedAttribute.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-PutExtendedAttribute.java" >}}

{{< /tab >}}

{{< /tabs >}}
