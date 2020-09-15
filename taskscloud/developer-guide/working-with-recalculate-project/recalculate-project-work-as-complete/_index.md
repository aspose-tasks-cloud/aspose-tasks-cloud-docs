---
title: "Recalculate Project Work as Complete"
type: docs
url: /recalculate-project-work-as-complete/
weight: 40
---

# **Introduction**
This example allows you to recalculate project work as complete using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, Objective C, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/recalculate/projectWorkAsComplete|PUT|Recalculate project work as complete|[PutRecalculateProjectWorkAsComplete](https://apireference.aspose.cloud/tasks/#/TasksRecalculate/PutRecalculateProjectWorkAsComplete)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v http://api.aspose.cloud/v3.0/tasks/{documentname}/recalculate/projectWorkAsComplete?appsid=xxxx&signature=xxxx \

     -X PUT \

	 -H "Content-Type: application/json" \

     -H "Accept: application/json"  



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
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="Perl" tabName3="Java" tabName4="Python" tabName5="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Tasks-RecalculateProjectWorkAsComplete-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Tasks-RecalculateProjectWorkAsComplete-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-working-RecalculateProjectAsCompleteExample-1.java" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "ac11b29d2d4ca102fb9628c918b32f2a" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "d677dbd1751c139c49dbaab88e29b418" >}}

{{< /tab >}}

{{< /tabs >}}
