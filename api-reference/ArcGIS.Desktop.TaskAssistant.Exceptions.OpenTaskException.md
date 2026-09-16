# OpenTaskException

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.html">TaskAssistant</a>.<a class="xref" href="ArcGIS.Desktop.TaskAssistant.Exceptions.html">Exceptions</a>
- Assembly: ArcGIS.Desktop.TaskAssistant.dll

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Exceptions.OpenTaskException.yml" sourcestartlinenumber="1">Represents an error exception when opening an ArcGIS Pro .esriTasks file.</p>


## Object Signature

```csharp
public sealed class OpenTaskException : TaskException, ISerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.TaskAssistant.Exceptions.OpenTaskException.yml" sourcestartlinenumber="1">The OpenTaskException is thrown from the <xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.OpenTaskFileAsync(System.String)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.OpenTaskFileAsync(System.String%2cSystem.Guid)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.OpenTaskItemAsync(System.Guid)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.OpenTaskItemAsync(System.Guid%2cSystem.Guid)" data-throw-if-not-resolved="false"></xref>, or
<xref href="ArcGIS.Desktop.TaskAssistant.TaskAssistantFactory.GetTaskItemInfoAsync(System.String)" data-throw-if-not-resolved="false"></xref> methods.<br>
Use the <xref href="System.Exception.Message?text=Message" data-throw-if-not-resolved="false"></xref> property to determine the error in opening the task file.</p>





