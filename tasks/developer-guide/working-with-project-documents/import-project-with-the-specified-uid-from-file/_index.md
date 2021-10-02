---
title: "Import Project with the specified UID from File"
description: "Aspose.Tasks Cloud allows you to import project with the specified uid from file in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /import-project-with-the-specified-uid-from-file/
weight: 40
---

## **Introduction**
This example explains shows how to import project from primavera db formats (Primavera SQLite .db or Primavera xml) and save it to specified file with the specified format, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/import|PUT|Imports project from primavera db formats (Primavera SQLite .db or Primavera xml) and saves it to specified file with the specified format|[PutImportProjectFromFile](https://apireference.aspose.cloud/tasks/#/TasksDocument/PutImportProjectFromFile)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/p6_multiproject.xml/import?projectUid=111&filename=imported_from_primavera.xml&fileType=PrimaveraXml&outputFileFormat=p6xml" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"


```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
   "Code":200,
   "Status":"OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName6="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutImportProjectFromFile.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putImportProjectFromFile.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "4ddd4d2f36e5a2c5a192ea979782910d" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "61d5104daf4df6e9ff171ac6d3cb4db1" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutImportProjectFromFile.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-PutImportProjectFromFile.java" >}}

{{< /tab >}}

{{< /tabs >}}



