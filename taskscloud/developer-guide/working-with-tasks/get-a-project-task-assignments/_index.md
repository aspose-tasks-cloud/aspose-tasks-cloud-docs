---
title: "Get a Project Task Assignments"
type: docs
url: /get-a-project-task-assignments/
weight: 70
---

# **Introduction**
This example explains how to read information for a Project's task assignments.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}/assignments|GET|Read information for a Project Task Assignments|[GetTaskAssignments](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTaskAssignments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks/1/assignments" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjMzMDY0MTgsImV4cCI6MTU2MzM5MjgxOCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.MsIBVeVaYmx2nl8SQwNDxh1VbqojZgx287czkTUQp281ps55UnLoecpyiVJrSOKJooppGt\_dTnugj3ia8eO0eRww3OA1vDsiEje5asZGAnLL4AUeM\_2ka9n00UGzASWzuG5V4IuZir4TzpyveEYHWKER8XSyNF4JJ\_qD-09TqdLOFQAF2RPN0zFKT-HQ-Ja7d4ODyyob2eU3-6ezaxfPm5YT\_SnR8xPjLM\_CvtqvJROQOo9oQk6nnDal4lKDVmJ6iMo9B9Sg0gEY6Vg54Cr9fIHhuZLe7yJAwgSjJEBJ2c\_BWMsAdcjtCXwd9LPxWeCPD9kHYu6-9GvrC7XZ8blCqg"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"Assignments":{"List":[],"link":null},"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTaskAssignments.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-assinments-RetrieveAssignmentInformationExample-RetrieveAssignmentInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Assignments-GetProjectAssignments-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Assignments-get\_project\_assignments-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-assinments-RetrieveAssignmentInformationExample-RetrieveAssignmentInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Assignments-RetrieveAssignmentInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "5a669f28f52ee82a33e0b0e64643d26e" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "48428bbef0874075ee109f6c398424e8" >}}

{{< /tab >}}

{{< /tabs >}}
