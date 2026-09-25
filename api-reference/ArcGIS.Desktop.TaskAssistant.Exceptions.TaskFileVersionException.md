# TaskFileVersionException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Exceptions.TaskFileVersionException.yml" sourcestartlinenumber="1">Represents an error exception when the ArcGIS Pro .esriTasks file has the incorrect version.</p>


## Object Signature

```csharp
public sealed class TaskFileVersionException : TaskException, ISerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Exceptions.TaskFileVersionException.yml" sourcestartlinenumber="1">The TaskFileVersionException is thrown from the <xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.GetTaskItemInfoAsync(System.String)" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Desktop.TaskAssistant.TaskProjectItem.GetTaskItemInfoAsync" data-throw-if-not-resolved="false"></xref> methods.<br>
Use the <xref href="System.Exception.Message?text=Message" data-throw-if-not-resolved="false"></xref> property to determine the error in opening the task file.</p>





