---
title: "Get Project Assignment Items"
type: docs
url: /get-project-assignment-items/
weight: 10
---

# **Introduction**
This example explains how to read assignment information from a PowerPoint Presentation
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments|GET|Read assignment information from a MS Project File|[GetAssignments](https://apireference.aspose.cloud/tasks/#/TasksAssignments/GetAssignments)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant\_type=client\_credentials&client\_id=78946fb4-3bd4-4d3e-b309-f9e2ff9ac6f9&client\_secret=b125f13bf6b76ed81ee990142d841195" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/project\_2013.mpp/assignments" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjI5NjUyODMsImV4cCI6MTU2MzA1MTY4MywiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.FoEBnju-L64IPG4LC4cr3fPE9v-2r-ISWj0vOn-QP7vpUz5nw2v7pjbr7bn1ur5ljT0fR1Yofydu6nGqArTRZoqlR8LsHrEK5cbloN49B80Y6w\_slzSBj-1CRjNKpsk7kwB3miJzuEbRB5KeVU78arqkT70T2dZaehdGZ4Cj2DvVA9-ZmKPL9O89\_G8dT\_FIGDychhhuiNbuIkohQv7aU2byYFAM8ylKSHJE8FvjllQy0HtCmmZbyNBuLmf7ecdLvc0mxNiPzJscNoqkMobrzztkf6pIdG\_dfqWbkMCBWlnlb4WM-8twDTp4Z0n1Rt26lmmZY0AAgNQbxbsNUPTfWA"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java



```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="5" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetAssignments.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "1e014e1252ca7250adb1af1573a7a510" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "cd11fd03bb220f04239c5029e08f8ad7" >}}

{{< /tab >}}

{{< /tabs >}}
