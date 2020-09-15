---
title: "Aspose.Tasks Cloud 18.2 Release Notes"
type: docs
url: /aspose-tasks-cloud-18-2-release-notes/
weight: 70
---

{{% alert color="primary" %}} 

The page contains release notes for Aspose.Tasks Cloud update 18.2 – [API Reference](https://apireference.aspose.cloud/tasks/)

{{% /alert %}} 

\1) Added API for [reading Uids of projects in multiproject files](/get-uids-of-projects-in-multi-project-files/). 

\2) Added API for [importing the project with the specified UID from primavera db formats](/import-project-with-the-specified-uid-from-file/) (Primavera SQLite .db or Primavera xml). 

\3) Added API for [importing the project with the specified Uid from a public MS Project database specified by a connection string](/import-project-with-the-specified-uid-from-a-database/). 

\4) Changes in Task type:

![todo:image\_alt\_text](/images/icons/grey\_arrow\_down.png)

Details here...

- added field DurationText (The duration of a task entered by the user as a text)
- added field ExternalTaskProject (The source location and task identifier of an external task)
- added field ExternalId (If a task is an external task the property contains the task's external Id)
- added field StartText (Returns the task's start text)
- added field FinishText (Returns the task's finish text)
- added field ActualWorkProtected (The duration through which actual work is protected)
- added field ActualOvertimeWorkProtected (The duration through which actual overtime work is protected)
- added field IsResumeValid (Determines whether a task can be resumed)
- added field Stop (The date that represents the end of the actual portion of a task)
- added field ManualStart (Manually scheduled start of a task)
- added field ManualFinish (Manually scheduled finish of a task)
- added field ManualDuration(Defines manually scheduled duration of a task)
- added field NotesRTF (The text notes in RTF format)
- added field IgnoreWarnings (Indicates whether to hide the schedule conflict warning indicator in Microsoft Project)
- added field IsExpanded (Determines whether a summary task is expanded or not in GanttChart view)
- added field DisplayOnTimeline (Specifies whether a task should be displayed on a timeline view)
- added field DisplayAsSummary (Determines whether the task should be displayed as a summary task)
- added field Hyperlink (The title or explanatory text for a hyperlink associated with a task)
- added field HyperlinkAddress (The address for a hyperlink associated with a task)
- added field HyperlinkSubAddress (The specific location in a document in a hyperlink associated with a task)
- added field EarnedValueMethod (Determines whether the % Complete or Physical % Complete field should be used to calculate budgeted cost of work performed (BCWP))
- added field IsPublished (Determines whether the current task should be published to Project Server with the rest of the project)
- added field StatusManager (The name of the enterprise resource who is to receive status updates for the current task from resources)
- added field CommitmentStart (The start date of a delivery)
- added field CommitmentFinish (The finish date of a delivery)
- added field CommitmentType (Determines whether a task has an associated delivery or a dependency on an associated delivery)

\5) Changes in Resource type: 

![todo:image\_alt\_text](/images/icons/grey\_arrow\_down.png)

Details here...

- [Breaking] RateScale field (previously integer) now is limited to the following values: 'Undefined', 'Minute', 'Hour', 'Day', 'Week', 'Month', 'Quarter', 'Year'
- added field Guid (Contains the generated unique identification code for the resource)
- added field WindowsUserAccount (The NT account associated with a resource)
- added field Workgroup (The type of a workgroup to which a resource belongs)
- added field Notes (The text notes associated with a resource)
- added field NotesRTF (The text notes in RTF format)

\6) Added an API to [get the collection of work weeks of the specified calendar](/get-the-collection-of-work-weeks-of-the-specified-calendar/).

\7) Added an API to [get VBA Project](/get-vba-project/)

\8) Added an API to [move a Task to another position under the same Parent and the same Outline Level](/move-a-task-to-another-position-under-the-same-parent-and-the-same-outline-level/).

\9) **[Breaking]** [API for converting project file to the specified format is renamed](/convert-project-document-to-the-specified-format/). 

\10) Added an API to convert Project Document to the other Format with the specified Save Options

\11) **[Breaking]** Some enum field in API's objects were serialized to json as integer values. Now it's fixed.

![todo:image\_alt\_text](/images/icons/grey\_arrow\_down.png)

List of the affected fields...

|**Object**|**Field**|**Possible values**|
| :- | :- | :- |
|CalendarException|Type|Daily, YearlyByDay, YearlyByPosition, MonthlyByDay, MonthlyByPosition, Weekly, ByDayCount, ByWeekDayCount, NoExceptionType|
|CalendarException|DaysOfWeek|Array of the following values: Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Exception|
|CalendarException|MonthItem|Undefined, Day, Weekday, WeekendDay, Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday|
|CalendarException|Month|Undefined, January, February, March, April, May, June, July, August, September, October, November, December|
|CalendarException|MonthPosition|Undefined, First, Second, Third, Fourth, Last|
|Document|FileFormat|Undefined, P6XML, XML, MPP8, MPP9, MPP12, MPP14, MPT9, MPT12, MPT14, MPX, XER, HTML|
|ExtendedAttribute|DurationFormat|Minute, ElapsedMinute, Hour, ElapsedHour, Day, ElapsedDay, Week, ElapsedWeek, Month, ElapsedMonth, Percent, ElapsedPercent, Null, MinuteEstimated, ElapsedMinuteEstimated, HourEstimated, ElapsedHourEstimated, DayEstimated, ElapsedDayEstimated, WeekEstimated, ElapsedWeekEstimated, MonthEstimated, ElapsedMonthEstimated, PercentEstimated, ElapsedPercentEstimated, Year, Undefined|
|ExtendedAttributeDefinition|CfType|Null, Cost, Date, Duration, Finish, Flag, Number, Start, Text|
|ExtendedAttributeDefinition|ElementType|Null, Task, Resource|
|ExtendedAttributeDefinition|RollupType|Null, Maximum, Minimum, Count, Sum, Average, AverageFirstSublevel, CountFirstSublevel, CountNonsummaries|
|ExtendedAttributeDefinition|CalculationType|None, Lookup, Rollup, Calculation|
|OutlineMask|Type|Null, Numbers, UpperCaseLetters, LowerCaseLetters, Characters, Val4, Val5, Val6, Val7, Val8, Val9|
|OutlineValue|Type|Null, Date, Duration, Cost, Number, Flag, Text, FinishDate|
|RecurringInfo|RecurrencePattern|Daily, Weekly, Monthly, Yearly|
|RecurringInfo|WeeklyDays|None, Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday|
|RecurringInfo|MonthlyOrdinalNumber|First, Second, Third, Fourth, Last|
|RecurringInfo|MonthlyOrdinalDay|Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday|
|RecurringInfo|YearlyOrdinalNumber|First, Second, Third, Fourth, Last|
|RecurringInfo|YearlyOrdinalDay|Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday|
|RecurringInfo|YearlyOrdinalMonth|Undefined, January, February, March, April, May, June, July, August, September, October, November, December|
|Resource|Type|Material, Work, Cost|
|Resource|AccrueAt|Undefined, Start, Prorated, End, Invalid|
|Resource|StandardRateFormat|Minute, Hour, Day, Week, Month, Year, MaterialResourceRate, Undefined|
|Resource|OvertimeRateFormat|Minute, Hour, Day, Week, Month, Year, MaterialResourceRate, Undefined|
|Resource|BookingType|Undefined, Committed, Proposed|
|Assignment|CostRateTableType|Undefined, A, B, C, D, E|
|Assignment|LevelingDelayFormat|Same as ExtendedAttribute.DurationFormat|
|Assignment|WorkContour|Flat, BackLoaded, FrontLoaded, DoublePeak, EarlyPeak, LatePeak, Bell, Turtle, Contoured, Undefined|
|Assignment|BookingType|Undefined, Committed, Proposed|
|Task|ConstraintType|AsSoonAsPossible, AsLateAsPossible, MustStartOn, MustFinishOn, StartNoEarlierThan, StartNoLaterThan, FinishNoEarlierThan, FinishNoLaterThan, Undefined|
|Task|FixedCostAccrual|Undefined, Start, Prorated, End, Invalid|
|Task|Type|Undefined, FixedUnits, FixedDuration, FixedWork|
|Task|LevelingDelayFormat|Same as ExtendedAttribute.DurationFormat|
|TaskLink|LinkType|FinishToFinish, FinishToStart, StartToFinish, StartToStart|
|TaskLink|LagFormat|Same as ExtendedAttribute.DurationFormat|
|TimephasedData|Unit|Same as ExtendedAttribute.DurationFormat|
|TimephasedData|TimephasedDataType|AssignmentRemainingWork, AssignmentActualWork, AssignmentActualOvertimeWork, AssignmentBaselineWork, AssignmentBaselineCost, AssignmentActualCost, ResourceBaselineWork, ResourceBaselineCost, TaskBaselineWork, TaskBaselineCost, TaskPercentComplete, AssignmentBaseline1Work, AssignmentBaseline1Cost, TaskBaseline1Work, TaskBaseline1Cost, ResourceBaseline1Work, ResourceBaseline1Cost, AssignmentBaseline2Work, AssignmentBaseline2Cost, TaskBaseline2Work, TaskBaseline2Cost, ResourceBaseline2Work, ResourceBaseline2Cost, AssignmentBaseline3Work, AssignmentBaseline3Cost, TaskBaseline3Work, TaskBaseline3Cost, ResourceBaseline3Work, ResourceBaseline3Cost, AssignmentBaseline4Work, AssignmentBaseline4Cost, TaskBaseline4Work, TaskBaseline4Cost, ResourceBaseline4Work, ResourceBaseline4Cost, AssignmentBaseline5Work, AssignmentBaseline5Cost, TaskBaseline5Work, TaskBaseline5Cost, ResourceBaseline5Work, ResourceBaseline5Cost, AssignmentBaseline6Work, AssignmentBaseline6Cost, TaskBaseline6Work, TaskBaseline6Cost, ResourceBaseline6Work, ResourceBaseline6Cost, AssignmentBaseline7Work, AssignmentBaseline7Cost, TaskBaseline7Work, TaskBaseline7Cost, ResourceBaseline7Work, ResourceBaseline7Cost, AssignmentBaseline8Work, AssignmentBaseline8Cost, TaskBaseline8Work, TaskBaseline8Cost, ResourceBaseline8Work, ResourceBaseline8Cost, AssignmentBaseline9Work, AssignmentBaseline9Cost, TaskBaseline9Work, TaskBaseline9Cost, ResourceBaseline9Work, ResourceBaseline9Cost, AssignmentBaseline10Work, AssignmentBaseline10Cost, TaskBaseline10Work, TaskBaseline10Cost, ResourceBaseline10Work, ResourceBaseline10Cost, PhysicalPercentComplete, TaskWork, TaskCost, ResourceWork, ResourceCost, AssignmentWork, AssignmentCost, Undefined|
|WBSCodeMask|Sequence|OrderedNumbers, OrderedUppercaseLetters, OrderedLowercaseLetters, UnorderedCharacters|
|WeekDay|DayType|Sunday, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Exception|

\12) API [tasks/{filename}/recalculate/project](/recalculate-project/) now have boolean parameter "validate" which specifies that validation should be performed before the recalculation.

\13) An API added to get page count for the project to be rendered using specified time interval and given timescale. You can also specify Presentation format and Page size.

\14) An API added to [add a new Extended Attribute definition to a Project](/add-a-new-extended-attribute-definition-to-a-project/).

\15) An API added to [get timescaled data for a task, resource and assignment with the specified Uid](/get-timescaled-data/).

\16) Change in CalendarException type: 

- added Index field (Index of the current item in the collection of calendar's exceptions)

\17) **[Breaking]** The DELETE request to the following endpoints now return 404 NotFound status if the specified entity is not found. Previously returned status was: 200 OK

![todo:image\_alt\_text](/images/icons/grey\_arrow\_down.png)

Details here...

DELETE   /tasks/[test.mpp/assignments/1](http://test.mpp/assignments/1)

DELETE   /tasks/[test.mpp/calendars/1](http://test.mpp/calendars/1)

DELETE   /tasks/[test.mpp/calendars/1/](http://test.mpp/calendars/1/)calendarExceptions/1

DELETE   /tasks/[test.mpp/extendedAttributes/1](http://test.mpp/extendedAttributes/1)

DELETE   /tasks/[test.mpp/outlineCodes/1](http://test.mpp/outlineCodes/1)

DELETE   /tasks/[test.mpp/resources/1](http://test.mpp/resources/1)

DELETE   /tasks/[test.mpp/tasks/1](http://test.mpp/tasks/1)

DELETE   /tasks/[test.mpp/taskLinks/1](http://test.mpp/taskLinks/1)



\18) **[Breaking]** Baseline-related properties are moved from the following types: Task, Resource, Assignment to the nested arrrays. 

![todo:image\_alt\_text](/images/icons/grey\_arrow\_down.png)

Details here...

Task json was (non-relevantfieldsareommitted):

```java

{

... 

"LevelingDelayFormat": "Minute",

"BaselineStart" : "0001-01-01T00:00:00",

"BaselineFinish" : "0001-01-01T00:00:00",

"BaselineDuration" : "0.00:00:00",

"BaselineFixedCost" : 0,

"BaselineDurationFormat" : "Minute", 

"BaselineEstimatedDuration" : false,

"BaselineWork" : "0.00:00:00",

"BaselineCost" : 0,

"BaselineBcws" : 0,

"BaselineBcwp" : 0,

"Baseline1Start" : "0001-01-01T00:00:00",

"Baseline1Finish" : "0001-01-01T00:00:00",

"Baseline1Duration" : "PT0S",

"Baseline1FixedCost" : 0,

"Baseline1DurationFormat" : "Minute", 

"Baseline1EstimatedDuration" : false,

"Baseline1Work" : "0.00:00:00",

"Baseline1Cost" : 0,

"Baseline1Bcws" : 0,

"Baseline1Bcwp" : 0,

...             (All baselines are listed, even not set ones)

"Baseline5Start": "2002-10-10T00:00:00+07:00",

"Baseline5Finish": "2002-12-10T00:00:00+06:00",

"Baseline5Duration": "35.00:00:00",

"Baseline5FixedCost": 24.0,

"Baseline5DurationFormat": "Hour",

"Baseline5EstimatedDuration": false,

"Baseline5Work": "00:00:00",

"Baseline5Cost": 22.0,

"Baseline5Bcws": 0.0,

"Baseline5Bcwp": 0.0

....          

"Baseline10Start" : "0001-01-01T00:00:00",

"Baseline10Finish" : "0001-01-01T00:00:00",

"Baseline10Duration" : "0.00:00:00",

"Baseline10FixedCost" : 0,

"Baseline10DurationFormat" : "Minute", 

"Baseline10EstimatedDuration" : false,

"Baseline10Work" : "0.00:00:00",

"Baseline10Cost" : 0,

"Baseline10Bcws" : 0,

"Baseline10Bcwp" : 0,

"ExtendedAttributes": [

....

}

```

Now:

```java

{

... 

"LevelingDelayFormat": "Minute",

"Baselines": [

{

    "Start": "2002-10-10T00:00:00+07:00",

    "Finish": "2002-12-10T00:00:00+06:00",

    "Duration": "35.00:00:00",

    "FixedCost": 24.0,

    "DurationFormat": "Hour",

    "EstimatedDuration": false,

    "BaselineNumber": "Baseline5",

    "Work": "00:00:00",

    "Cost": 22.0,

    "Bcws": 0.0,

    "Bcwp": 0.0

}],

"ExtendedAttributes": [

...

}

```



