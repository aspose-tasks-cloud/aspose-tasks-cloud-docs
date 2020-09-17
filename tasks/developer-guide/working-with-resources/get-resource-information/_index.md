---
title: "Get Resource Information"
type: docs
url: /get-resource-information/
weight: 10
---

# **Introduction**
This example allows you to get a resource information using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/resources|GET|Read Resource Information for a MS Project|[GetResources](https://apireference.aspose.cloud/tasks/#/TasksResources/GetResources)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X GET "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/resources" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NjMzMDY0MTgsImV4cCI6MTU2MzM5MjgxOCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiOWYwYjI2ZDEtMGYxZi00MDNiLTliYTQtMTMzMzk4MGFjNmRiIiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.MsIBVeVaYmx2nl8SQwNDxh1VbqojZgx287czkTUQp281ps55UnLoecpyiVJrSOKJooppGt_dTnugj3ia8eO0eRww3OA1vDsiEje5asZGAnLL4AUeM_2ka9n00UGzASWzuG5V4IuZir4TzpyveEYHWKER8XSyNF4JJ_qD-09TqdLOFQAF2RPN0zFKT-HQ-Ja7d4ODyyob2eU3-6ezaxfPm5YT_SnR8xPjLM_CvtqvJROQOo9oQk6nnDal4lKDVmJ6iMo9B9Sg0gEY6Vg54Cr9fIHhuZLe7yJAwgSjJEBJ2c_BWMsAdcjtCXwd9LPxWeCPD9kHYu6-9GvrC7XZ8blCqg"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{"Resources":{"ResourceItem":[{"Link":{"Href":"/0","Rel":"self","Type":null,"Title":null},"Uid":0,"Id":0,"Name":null},{"Link":{"Href":"/1","Rel":"self","Type":null,"Title":null},"Uid":1,"Id":1,"Name":"Resource1"},{"Link":{"Href":"/2","Rel":"self","Type":null,"Title":null},"Uid":2,"Id":2,"Name":"Resource2"},{"Link":{"Href":"/3","Rel":"self","Type":null,"Title":null},"Uid":3,"Id":3,"Name":"Resource3"},{"Link":{"Href":"/4","Rel":"self","Type":null,"Title":null},"Uid":4,"Id":4,"Name":"Resource4"},{"Link":{"Href":"/5","Rel":"self","Type":null,"Title":null},"Uid":5,"Id":5,"Name":"Resource5"}],"link":{"Href":"/resources","Rel":"self","Type":null,"Title":null}},"Code":200,"Status":"OK"}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-Resources-RetrieveResourceInformation-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-resources-RetrieveResourceInformationExample-RetrieveResourceInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Resources-GetProjectResource-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Resources-get_project_resource-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-resources-RetrieveResourceInformationExample-RetrieveResourceInformationExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-Resources-RetrieveResourceInformation-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "609984135cbfda7cd73bcc683405e68d" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "c34b7894a56a66b0313cfb639d5b1efd" >}}

{{< /tab >}}

{{< /tabs >}}
