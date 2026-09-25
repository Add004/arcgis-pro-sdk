# IJobsManager

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Provides access to the jobs within Workflow Manager.</p>


## Object Signature

```csharp
public interface IJobsManager
```


## Members

### AssignCurrentStep(string, AssignedType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Assign the current step of a job.</p>


```csharp
void AssignCurrentStep(string jobId, AssignedType assignedType, string assignedTo)
```
### AssignStep(string, string, AssignedType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Assign one of the current steps on a job.</p>


```csharp
void AssignStep(string jobId, string stepId, AssignedType assignedType, string assignedTo)
```
### CalculateJobStatistics(JobStatisticsQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Returns the count of total records that match the query results provided in the query.</p>


```csharp
JobStatistics CalculateJobStatistics(JobStatisticsQuery query)
```
### FinishSteps(string, List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Finishes running the steps in the array, and proceeds to the next step(s).
If no stepIds are specified, then all the current steps will be finished.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void FinishSteps(string jobId, List<string> stepIds = null)
```
### GetJob(string, bool, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Get the details of a job by jobId. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
Job GetJob(string jobId, bool extProps = false, bool holds = false)
```
### GetJobId()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Gets the job Id associated with the active map view. This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
string GetJobId()
```
### GetJobId(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Gets the job Id associated with the map. This method must be called on the MCT.Use QueuedTask.Run.</p>


```csharp
string GetJobId(string mapUri)
```
### RunSteps(string, List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Starts running the steps provided in the array.Running a step marks it as finished, if the step is set to proceed to next.
If no stepIds are specified, then all the current steps will be started.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void RunSteps(string jobId, List<string> stepIds = null)
```
### SearchJobs(SearchQuery)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Search for jobs in the system.</p>


```csharp
SearchResult SearchJobs(SearchQuery query)
```
### SetCurrentStep(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Sets a single step to be the active step on the job.</p>


```csharp
void SetCurrentStep(string jobId, string stepId)
```
### StopSteps(string, List&lt;string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.IJobsManager.yml" sourcestartlinenumber="1">Stops running the steps in the array. Each step can be Run again or Finish can be used to complete them.
In case of GP step and question step, the processing of each step is cancelled.
In case of manual and open app step, each step is paused. Each step can be forced to stop by a
user not assigned to the step with the jobForceStop privilege.
If no stepIds are specified, then all the current steps will be stopped.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
void StopSteps(string jobId, List<string> stepIds = null)
```


