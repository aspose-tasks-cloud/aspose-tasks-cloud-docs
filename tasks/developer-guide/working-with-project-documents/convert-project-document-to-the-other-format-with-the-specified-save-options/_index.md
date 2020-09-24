---
title: "Convert Project Document to the other Format with the specified Save Options"
type: docs
url: /convert-project-document-to-the-other-format-with-the-specified-save-options/
weight: 20
---

## **Introduction**
This example allows you to convert Project document to the other format with the specified Save Options. SaveOptions parameter of POST format endpoint for 'pdf', 'html' and image formats supports "ReduceFooterGap" field. The API returns stream response with project file in the specified format. The 'format' parameter can have the following possible values: 

- mpp
- xml
- html
- bmp
- png
- jpeg
- pdf
- tiff
- xps
- svg
- csv
- txt
- spreadsheetML
- xlsx
- p6xml
- xer
- mpx
- Gdhtml
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/format|POST|Get a project document in the specified format and with the specified save options|[PostTaskDocumentWithFormat](https://apireference.aspose.cloud/tasks/#/TasksDocument/PostTaskDocumentWithFormat)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/format?format=csv&returnAsZipArchive=false" -H "accept: multipart/form-data" -H "x-aspose-client: Containerize.Swagger" -d '{ "TextDelimiter":"Comma", "IncludeHeaders":false, "NonExistingTestProperty":false, "View":{ "Columns":             [{"Type":"GanttChartColumn","Name":"TestColumn1","Property":"Name","Width":120},{"Type":"GanttChartColumn","Name":"TestColumn2","Property":"Duration","Width":120}]}}'

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
{{< tabs tabTotal="1" tabID="4" tabName1="C#" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-PostTaskDocumentWithFormat.cs" >}}

{{< /tab >}}

{{< /tabs >}}
