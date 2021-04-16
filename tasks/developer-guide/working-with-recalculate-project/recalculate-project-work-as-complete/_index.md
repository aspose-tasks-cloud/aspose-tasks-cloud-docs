---
title: "Recalculate Project Work as Complete"
type: docs
url: /recalculate-project-work-as-complete/
weight: 40
---

## **Introduction**
This example allows you to recalculate project work as complete using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/recalculate/projectWorkAsComplete|PUT|Recalculate project work as complete|[PutRecalculateProjectWorkAsComplete](https://apireference.aspose.cloud/tasks/#/TasksRecalculate/PutRecalculateProjectWorkAsComplete)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/sample-project-2.mpp/recalculate/projectWorkAsComplete?setZeroOrHundredPercentCompleteOnly=true" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "2020-09-19T12:30:29.720Z"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "Code": 200,
  "Status": "OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutRecalculateProjectWorkAsComplete.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putRecalculateProjectWorkAsComplete.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "ac11b29d2d4ca102fb9628c918b32f2a" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "d677dbd1751c139c49dbaab88e29b418" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutRecalculateProjectWorkAsComplete.go" >}}

{{< /tab >}}

{{< /tabs >}}
