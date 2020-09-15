---
title: "Get Specific Calendar of a Project"
type: docs
url: /get-specific-calendar-of-a-project/
weight: 20
---

# **Introduction**
This example allows you to retrieve a project calendar information of specified UID.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}|GET|Read information for a specific calendar by UID|[GetCalendar](https://apireference.aspose.cloud/tasks/#/TasksCalendar/GetCalendar)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjMzMDY0MTgsImV4cCI6MTU2MzM5MjgxOCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.MsIBVeVaYmx2nl8SQwNDxh1VbqojZgx287czkTUQp281ps55UnLoecpyiVJrSOKJooppGt\_dTnugj3ia8eO0eRww3OA1vDsiEje5asZGAnLL4AUeM\_2ka9n00UGzASWzuG5V4IuZir4TzpyveEYHWKER8XSyNF4JJ\_qD-09TqdLOFQAF2RPN0zFKT-HQ-Ja7d4ODyyob2eU3-6ezaxfPm5YT\_SnR8xPjLM\_CvtqvJROQOo9oQk6nnDal4lKDVmJ6iMo9B9Sg0gEY6Vg54Cr9fIHhuZLe7yJAwgSjJEBJ2c\_BWMsAdcjtCXwd9LPxWeCPD9kHYu6-9GvrC7XZ8blCqg"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 {

   "Calendar":{

      "Name":"Standard",

      "Uid":1,

      "Days":[

         {

            "DayType":"Sunday",

            "DayWorking":false,

            "FromDate":"0001-01-01T00:00:00",

            "ToDate":"0001-01-01T00:00:00",

            "WorkingTimes":[

            ]

         },

         {

            "DayType":"Monday",

            "DayWorking":true,

            "FromDate":"0001-01-01T00:00:00",

            "ToDate":"0001-01-01T00:00:00",

            "WorkingTimes":[

               {

                  "FromTime":"0010-01-01T08:00:00Z",

                  "ToTime":"0010-01-01T12:00:00Z"

               },

               {

                  "FromTime":"0010-01-01T13:00:00Z",

                  "ToTime":"0010-01-01T17:00:00Z"

               }

            ]

         },

         {

            "DayType":"Tuesday",

            "DayWorking":true,

            "FromDate":"0001-01-01T00:00:00",

            "ToDate":"0001-01-01T00:00:00",

            "WorkingTimes":[

               {

                  "FromTime":"0010-01-01T08:00:00Z",

                  "ToTime":"0010-01-01T12:00:00Z"

               },

               {

                  "FromTime":"0010-01-01T13:00:00Z",

                  "ToTime":"0010-01-01T17:00:00Z"

               }

            ]

         },

         {

            "DayType":"Wednesday",

            "DayWorking":true,

            "FromDate":"0001-01-01T00:00:00",

            "ToDate":"0001-01-01T00:00:00",

            "WorkingTimes":[

               {

                  "FromTime":"0010-01-01T08:00:00Z",

                  "ToTime":"0010-01-01T12:00:00Z"

               },

               {

                  "FromTime":"0010-01-01T13:00:00Z",

                  "ToTime":"0010-01-01T17:00:00Z"

               }

            ]

         },

         {

            "DayType":"Thursday",

            "DayWorking":true,

            "FromDate":"0001-01-01T00:00:00",

            "ToDate":"0001-01-01T00:00:00",

            "WorkingTimes":[

               {

                  "FromTime":"0010-01-01T08:00:00Z",

                  "ToTime":"0010-01-01T12:00:00Z"

               },

               {

                  "FromTime":"0010-01-01T13:00:00Z",

                  "ToTime":"0010-01-01T17:00:00Z"

               }

            ]

         },

         {

            "DayType":"Friday",

            "DayWorking":true,

            "FromDate":"0001-01-01T00:00:00",

            "ToDate":"0001-01-01T00:00:00",

            "WorkingTimes":[

               {

                  "FromTime":"0010-01-01T08:00:00Z",

                  "ToTime":"0010-01-01T12:00:00Z"

               },

               {

                  "FromTime":"0010-01-01T13:00:00Z",

                  "ToTime":"0010-01-01T17:00:00Z"

               }

            ]

         },

         {

            "DayType":"Saturday",

            "DayWorking":false,

            "FromDate":"0001-01-01T00:00:00",

            "ToDate":"0001-01-01T00:00:00",

            "WorkingTimes":[

            ]

         }

      ],

      "IsBaseCalendar":true,

      "BaseCalendar":null,

      "IsBaselineCalendar":false

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

{{< gist "aspose-cloud" "040930fc8c6b8b8970da8772f10ba0a7" "Examples-.NET-GetCalendar.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-calendars-RetreiveCalendarInformationExample-RetreiveCalendarInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Calendars-GetProjectCalendars-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Calendars-get\_project\_calendars-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-calendars-RetreiveCalendarInformationExample-RetreiveCalendarInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Calendars-RetrieveCalendarInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "d0d4fdd8be8ef30822a118dce82a8693" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "fc590b9d24cc725817f34d92451106f7" >}}

{{< /tab >}}

{{< /tabs >}}
