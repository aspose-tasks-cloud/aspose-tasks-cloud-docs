---
title: "Import Project with the specified UID from a Database"
type: docs
url: /import-project-with-the-specified-uid-from-a-database/
weight: 50
---

## **Introduction**
This example explains how to import Project with the specified UID from a MS Project Database specified by a connection string and saves it to specified file with the specified format. 
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
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-PutImportProjectFromDb.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "7b4598fd3018a3c84245c237b9ad4f6e" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "bdc961a56579a3daf13ec4e73e07ab02" >}}

{{< /tab >}}

{{< /tabs >}}
