---
title: "Get Outline Code By Index"
type: docs
url: /get-outline-code-by-index/
weight: 20
---

## **Introduction**
This example allows you to get Outline Code by index using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/outlineCodes/{index}|GET|Read outline codes by index information from a MS Project file|[GetOutlineCodeByIndex](https://apireference.aspose.cloud/tasks/#/TasksOutlineCodes/GetOutlineCodeByIndex)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/outlineCodes/1" -H "accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "code": 0,
  "status": "string",
  "outlineCode": {
    "guid": "string",
    "fieldId": "string",
    "fieldName": "string",
    "alias": "string",
    "phoneticAlias": "string",
    "values": [
      {
        "valueId": 0,
        "fieldGuid": "string",
        "type": "Null",
        "parentValueId": 0,
        "value": "string",
        "description": "string",
        "isCollapsed": true
      }
    ],
    "enterprise": true,
    "enterpriseOutlineCodeAlias": 0,
    "resourceSubstitutionEnabled": true,
    "leafOnly": true,
    "allLevelsRequired": true,
    "onlyTableValuesAllowed": true,
    "masks": [
      {
        "level": 0,
        "type": "Null",
        "length": 0,
        "separator": "string"
      }
    ],
    "showIndent": true
  }
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNet-CSharp-CodesAndExtendedAttributes-GetCodeByIndex-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-outlinecodes-GetOutlineCodeByIndexExample-GetOutlineCodeByIndexExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-OutlineCodesAndExtendedAttributes-GetOutlineCodeByIndex-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-OutlineCodesAndExtendedAttributes-get_outline_code_by_index-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-outlinecodes-GetOutlineCodeByIndexExample-GetOutlineCodeByIndexExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-CodesAndExtendedAttributes-GetCodeByIndex-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "8063d999260e8db44b685d7bc25fdefa" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "19ffc760e4231be39030ec751d5592cf" >}}

{{< /tab >}}

{{< /tabs >}}
