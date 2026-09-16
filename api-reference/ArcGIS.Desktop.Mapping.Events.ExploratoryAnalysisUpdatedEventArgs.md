# ExploratoryAnalysisUpdatedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ExploratoryAnalysisUpdatedEventArgs.yml" sourcestartlinenumber="1">Event arguments provided when an exploratory analysis object has been updated.</p>


## Object Signature

```csharp
public class ExploratoryAnalysisUpdatedEventArgs : EventArgs
```


## Members

### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ExploratoryAnalysisUpdatedEventArgs.yml" sourcestartlinenumber="1">Gets the ID of the updated exploratory analysis object.  Use this in conjunction with MapView to uniquely
identify an exploratory analysis object.</p>


```csharp
public int ID { get; }
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.ExploratoryAnalysisUpdatedEventArgs.yml" sourcestartlinenumber="1">Gets the MapView that the updated exploratory analysis object belongs to.  Use this in conjunction with Id to uniquely
identify an exploratory analysis object.</p>


```csharp
public MapView MapView { get; }
```


