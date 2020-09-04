---
title: "Edit Specific Resource Assignment"
type: docs
url: /edit-specific-resource-assignment/
weight: 60
---

# **Introduction**
This example explains how to edit a resource assignment within a MS Project file using a resource identifier
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments/{assignmentUid}|PUT|Update a Resource in a MS Project file using a identifer|[PutAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/PutAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -v "https://api.aspose.cloud/connect/token" -X POST -d "grant\_type=client\_credentials&client\_id=78946fb4-3bd4-4d3e-b309-f9e2ff9ac6f9&client\_secret=b125f13bf6b76ed81ee990142d841195" -H "Content-Type: application/x-www-form-urlencoded" -H "Accept: application/json"

```

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/assignments/1?mode=1&recalculate=true" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjI5NjgwOTUsImV4cCI6MTU2MzA1NDQ5NSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.YesjZfTmxKi7TiKAzBPOZj2jkbWZifAzyJe8nULhCpchlPilLYVLZ0ph6OBF-n4JGOeXhyck3zGORn3TP6wT\_HjFzzHGmZr9aPZnQqVU4Ypch8MnmgPgdeRZ\_L-FVNHq042w5A2zyUUZb9HFk67um7\_vAnuTXWxcHaK6\_mP2jG4vMAiE5MdxfUAylDQNymBRsiMivxgX5a3i2E2eUSCAs7ghpvdlVxHVcyjFg5GX26V67iD-FFqJDihoG6oyTAAJzTRnvxOb3jmNGo2Sav5VmmgkGeuHzDgdTYLJKGMZwXjIKdwx0Vuz-U5ilfbe-XHoqPha3pE5bD7ByjbfR5hnuw" -H "Content-Type: application/json" -d "{ \"TaskUid\": 0, \"ResourceUid\": 0, \"Uid\": 0, \"PercentWorkComplete\": 0, \"ActualCost\": 0, \"ActualFinish\": \"2019-07-12T22:10:41.984Z\", \"ActualOvertimeCost\": 0, \"ActualOvertimeWork\": \"string\", \"ActualStart\": \"2019-07-12T22:10:41.984Z\", \"ActualWork\": \"string\", \"Acwp\": 0, \"Confirmed\": true, \"Cost\": 0, \"CostVariance\": 0, \"Cv\": 0, \"Delay\": 0, \"Finish\": \"2019-07-12T22:10:41.984Z\", \"FinishVariance\": 0, \"Hyperlink\": \"string\", \"HyperlinkAddress\": \"string\", \"HyperlinkSubAddress\": \"string\", \"WorkVariance\": 0, \"HasFixedRateUnits\": true, \"FixedMaterial\": true, \"LevelingDelay\": 0, \"LinkedFields\": true, \"Milestone\": true, \"Notes\": \"string\", \"Overallocated\": true, \"OvertimeCost\": 0, \"OvertimeWork\": \"string\", \"PeakUnits\": 0, \"RegularWork\": \"string\", \"RemainingCost\": 0, \"RemainingOvertimeCost\": 0, \"RemainingOvertimeWork\": \"string\", \"RemainingWork\": \"string\", \"ResponsePending\": true, \"Start\": \"2019-07-12T22:10:41.984Z\", \"Stop\": \"2019-07-12T22:10:41.984Z\", \"Resume\": \"2019-07-12T22:10:41.984Z\", \"StartVariance\": 0, \"Summary\": true, \"Sv\": 0, \"Units\": 0, \"UpdateNeeded\": true, \"Vac\": 0, \"Work\": \"string\", \"Bcws\": 0, \"Bcwp\": 0, \"ActualWorkProtected\": \"string\", \"ActualOvertimeWorkProtected\": \"string\", \"CreationDate\": \"2019-07-12T22:10:41.984Z\", \"AssnOwner\": \"string\", \"AssnOwnerGuid\": \"string\", \"BudgetCost\": 0, \"BudgetWork\": \"string\", \"Baselines\": [ { \"Work\": \"string\", \"Cost\": 0, \"Bcws\": 0, \"Bcwp\": 0, \"Start\": \"2019-07-12T22:10:41.984Z\", \"Finish\": \"2019-07-12T22:10:41.984Z\" } ], \"ExtendedAttributes\": [ { \"FieldId\": \"string\", \"ValueGuid\": \"string\", \"LookupValueId\": 0, \"DurationValue\": { \"TimeSpan\": \"string\" }, \"NumericValue\": 0, \"DateValue\": \"2019-07-12T22:10:41.984Z\", \"FlagValue\": true, \"TextValue\": \"string\" } ]}"

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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-EditAssignment.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< /tab >}}

{{< /tabs >}}
