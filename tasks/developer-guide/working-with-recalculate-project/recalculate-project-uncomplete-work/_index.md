---
title: "Recalculate Project Uncomplete Work"
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
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Perl" tabName3="Java" tabName4="Python" tabName5="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Tasks-RecalculateProjectUncompleteWorkToStartAfter-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Tasks-RecalculateProjectUncompleteWorkToStartAfter-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-working-RecalculateProjectUnCompleteExample-1.java" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "a1eae08739937d4797ba3b28620bbfef" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "6675976985a268f733cd4796aa3ffb31" >}}

{{< /tab >}}

{{< /tabs >}}
