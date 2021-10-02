---
title: "Convert MS Project To MPP"
description: "Aspose.Tasks Cloud allows you to convert ms project document to MPP. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /convert-ms-project-to-mpp/
weight: 10
---

## **Introduction**
This example explains how to convert MS Project to mpp. To do this, you must call specified endpoint. You also should specify at least some of required parameters. In this case, if you want to get output file in MPP format, you should set 'mpp' value for 'format' parameter. Name of uploaded input file is also required.

## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/format|GET|Get the project in a particular format|[GetTaskDocumentWithFormat](https://apireference.aspose.cloud/tasks/#/TasksDocument/GetTaskDocumentWithFormat)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/format?format=csv&returnAsZipArchive=false" -H "accept: multipart/form-data" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

Return a project document.

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="6" tabID="5" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetTaskDocumentWithFormat.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getTaskDocumentWithFormat.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "7bdb983bee26ed632f2ba6b36042c61e" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "c0935242e43399a58204d4b32293ec8d" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetTaskDocumentWithFormat.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-GetTaskDocumentWithFormat.java" >}}

{{< /tab >}}

{{< /tabs >}}
