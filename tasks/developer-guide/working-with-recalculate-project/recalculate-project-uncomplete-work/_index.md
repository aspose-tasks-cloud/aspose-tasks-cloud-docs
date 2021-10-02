---
title: "Recalculate Project Uncomplete Work"
description: "Aspose.Tasks Cloud allows you to recalculate project uncomplete work in MPP, MPT and XML. Moreover, our REST API can be used with nearly all languages like .NET, Node.JS, Python, PHP, Go, Java and many more."
type: docs
url: /recalculate-project-uncomplete-work/
weight: 30
---

## **Introduction**
This example allows you to recalculate project un-complete work using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/recalculate/uncompleteWorkToStartAfter|PUT|Recalculate project uncomplete work|[PutRecalculateProjectUncompleteWorkToStartAfter](https://apireference.aspose.cloud/tasks/#/TasksRecalculate/PutRecalculateProjectUncompleteWorkToStartAfter)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/sample-project-2.mpp/recalculate/uncompleteWorkToStartAfter" -H "accept: application/json" -H "Content-Type: application/json" -H "x-aspose-client: Containerize.Swagger" -d "2020-09-19T12:28:14.687Z"

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
{{< tabs tabTotal="6" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" tabName5="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutRecalculateProjectUncompleteWorkToStartAfter.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putRecalculateProjectUncompleteWorkToStartAfter.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "a1eae08739937d4797ba3b28620bbfef" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "6675976985a268f733cd4796aa3ffb31" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-PutRecalculateProjectUncompleteWorkToStartAfter.go" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "778c73d65cee00b98af00c9a48e36147" "Examples-PutRecalculateProjectUncompleteWorkToStartAfter.java" >}}

{{< /tab >}}

{{< /tabs >}}
