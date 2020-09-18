---
title: "Get work week collection of calendar"
type: docs
url: /get-work-week-collection-of-calendar/
weight: 30
---

# **Introduction**
This example explains how to get the collection of work weeks of the specified calendar. 
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/workWeeks|GET|Read work week information for a give Calendar within a MS Project File|[GetCalendarWorkWeeks](https://apireference.aspose.cloud/tasks/#/TasksCalendar/GetCalendarWorkWeeks)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/workWeeks" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjMzMDY0MTgsImV4cCI6MTU2MzM5MjgxOCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.MsIBVeVaYmx2nl8SQwNDxh1VbqojZgx287czkTUQp281ps55UnLoecpyiVJrSOKJooppGt_dTnugj3ia8eO0eRww3OA1vDsiEje5asZGAnLL4AUeM_2ka9n00UGzASWzuG5V4IuZir4TzpyveEYHWKER8XSyNF4JJ_qD-09TqdLOFQAF2RPN0zFKT-HQ-Ja7d4ODyyob2eU3-6ezaxfPm5YT_SnR8xPjLM_CvtqvJROQOo9oQk6nnDal4lKDVmJ6iMo9B9Sg0gEY6Vg54Cr9fIHhuZLe7yJAwgSjJEBJ2c_BWMsAdcjtCXwd9LPxWeCPD9kHYu6-9GvrC7XZ8blCqg"

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "CalendarWorkWeeks": [

    {

      "Name": "Work week 1",

      "FromDate": "2018-01-01T00:00:00+07:00",

      "ToDate": "2018-01-07T23:59:00+07:00",

      "WeekDays": [

        {

          "DayType": "Monday",

          "DayWorking": true,

          "FromDate": "0001-01-01T00:00:00Z",

          "ToDate": "0001-01-01T00:00:00Z",

          "WorkingTimes": [

            {

              "FromTime": "0001-01-01T11:30:00+06:00",

              "ToTime": "0001-01-01T12:30:00+06:00"

            }

          ]

        },

        {

          "DayType": "Tuesday",

          "DayWorking": false,

          "FromDate": "0001-01-01T00:00:00Z",

          "ToDate": "0001-01-01T00:00:00Z",

          "WorkingTimes": []

        },

        {

          "DayType": "Wednesday",

          "DayWorking": true,

          "FromDate": "0001-01-01T00:00:00Z",

          "ToDate": "0001-01-01T00:00:00Z",

          "WorkingTimes": [

            {

              "FromTime": "0001-01-01T09:30:00+06:00",

              "ToTime": "0001-01-01T13:23:00+06:00"

            },

            {

              "FromTime": "0001-01-01T14:45:00+06:00",

              "ToTime": "0001-01-01T18:45:00+06:00"

            }

          ]

        },

        {

          "DayType": "Saturday",

          "DayWorking": true,

          "FromDate": "0001-01-01T00:00:00Z",

          "ToDate": "0001-01-01T00:00:00Z",

          "WorkingTimes": [

            {

              "FromTime": "0001-01-01T09:00:00+06:00",

              "ToTime": "0001-01-01T10:00:00+06:00"

            }

          ]

        }

      ]

    }

  ],

  "Code": 200,

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="3" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetCalendarWorkWeeks.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "1c9b883b7494105d23bc698ed86f19d4" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "19bbbecc45363d6611c08aa77150c0e8" >}}

{{< /tab >}}

{{< /tabs >}}
