---
title: "Get a Specific Task of a Project"
type: docs
url: /get-a-specific-task-of-a-project/
weight: 20
---

# **Introduction**
This example explains how to retrieve a project task of a specified UID.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}|GET|Read a specific task of a project|[GetTask](https://apireference.aspose.cloud/tasks/#/TasksTask/GetTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/tasks/0" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjMzMDY0MTgsImV4cCI6MTU2MzM5MjgxOCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.MsIBVeVaYmx2nl8SQwNDxh1VbqojZgx287czkTUQp281ps55UnLoecpyiVJrSOKJooppGt\_dTnugj3ia8eO0eRww3OA1vDsiEje5asZGAnLL4AUeM\_2ka9n00UGzASWzuG5V4IuZir4TzpyveEYHWKER8XSyNF4JJ\_qD-09TqdLOFQAF2RPN0zFKT-HQ-Ja7d4ODyyob2eU3-6ezaxfPm5YT\_SnR8xPjLM\_CvtqvJROQOo9oQk6nnDal4lKDVmJ6iMo9B9Sg0gEY6Vg54Cr9fIHhuZLe7yJAwgSjJEBJ2c\_BWMsAdcjtCXwd9LPxWeCPD9kHYu6-9GvrC7XZ8blCqg"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

   "Task":{

      "Uid":0,

      "Id":0,

      "Name":"Home Move",

      "Duration":"14.08:00:00",

      "Start":"2004-01-01T08:00:00",

      "Finish":"2004-03-01T17:00:00",

      "PercentComplete":0,

      "PercentWorkComplete":0,

      "IsActive":true,

      "ConstraintType":"AsSoonAsPossible",

      "DurationVariance":"14.08:00:00",

      "EarlyFinish":"2004-03-01T17:00:00",

      "EarlyStart":"2004-01-01T08:00:00",

      "FixedCostAccrual":"Prorated",

      "GUID":"FF388A76-8020-4B4C-8FE6-F6050CA3B36E",

      "LateFinish":"2004-03-01T17:00:00",

      "LateStart":"2004-01-01T08:00:00",

      "IsLevelAssignments":true,

      "CanLevelingSplit":true,

      "IsMarked":false,

      "IsMilestone":false,

      "IsCritical":true,

      "SubprojectName":null,

      "IsSummary":true,

      "SubtasksUids":[

         1,

         41,

         78,

         130,

         153,

         171

      ],

      "OutlineLevel":0,

      "PreLeveledFinish":"2004-03-01T17:00:00",

      "PreLeveledStart":"2004-01-01T08:00:00",

      "RemainingDuration":"14.08:00:00",

      "IsResumeValid":false,

      "ManualStart":"2004-01-01T08:00:00",

      "ManualFinish":"2004-03-01T17:00:00",

      "ManualDuration":"14.08:00:00",

      "Type":"FixedDuration",

      "Wbs":"0",

      "Priority":500,

      "LevelingDelayFormat":"ElapsedDay",

      "Predecessors":"",

      "Successors":"",

      "IsExpanded":true,

      "EarnedValueMethod":"PercentComplete",

      "Baselines":[

      ],

      "ExtendedAttributes":[

      ],

      "OutlineCodes":[

      ]

   },

   "Code":200,

   "Status":"OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetTaskByUid.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-working-RetrieveTaskInformationExample-RetrieveTaskInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Tasks-GetProjectTask-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Tasks-get\_project\_task-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-working-RetrieveTaskInformationExample-RetrieveTaskInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Tasks-RetrieveInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< /tab >}}

{{< /tabs >}}
