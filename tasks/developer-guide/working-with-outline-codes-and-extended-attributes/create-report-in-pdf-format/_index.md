---
title: "Create Report in PDF Format"
description: "Aspose.Tasks Cloud allows you to create report in pdf format in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /create-report-in-pdf-format/
weight: 40
---

## **Introduction**
This example allows you to returns created report in PDF format using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/report|GET|Returns created report in PDF format|[GetReportPdf](https://apireference.aspose.cloud/tasks/#/TasksReport/GetReportPdf)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/sample-project-2.mpp/report?type=WorkOverview" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}
{{< tab tabNum="2" >}}

```java

Returns a JSON/XML representation of a project outline code items.
Each outline code item has a link to get full outline code definition representation in the project.

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-GetReportPdf.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-getReportPdf.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "93abe10ff4eb53df4b5dd66a2cec5dc4" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "34a371f33b930c95ef7c00946d4d40b7" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-GetReportPdf.go" >}}

{{< /tab >}}

{{< /tabs >}}
