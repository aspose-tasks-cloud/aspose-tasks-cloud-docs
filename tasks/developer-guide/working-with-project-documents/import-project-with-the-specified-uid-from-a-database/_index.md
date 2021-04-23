---
title: "Import Project with the specified UID from a Database"
description: "Aspose.Tasks Cloud allows you to import project with the specified uid from a database in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /import-project-with-the-specified-uid-from-a-database/
weight: 50
---

## **Introduction**
This example explains how to import Project with the specified UID from a MS Project Database specified by a connection string and saves it to specified file with the specified format, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more. 
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/importfromdb|PUT|Imports project from database with the specified connection string and saves it to specified file with the specified format|[PutImportProjectFromDb](https://apireference.aspose.cloud/tasks/#/TasksDocument/PutImportProjectFromDb)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/importfromdb?databaseType=Msp&projectUid=E6426C44-D6CB-4B9C-AF16-48910ACE0F54&filename=imported_from_db.xml&format=p6xml&databaseSchema=dbo" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "Data Source=.\\\\SQLEXPRESS;Initial Catalog=ProjectServer_Published;Persist Security Info=True;User ID=sa;Password=pwd;"

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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutImportProjectFromDb.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putImportProjectFromDb.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "7b4598fd3018a3c84245c237b9ad4f6e" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "bdc961a56579a3daf13ec4e73e07ab02" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutImportProjectFromDb.go" >}}

{{< /tab >}}

{{< /tabs >}}
