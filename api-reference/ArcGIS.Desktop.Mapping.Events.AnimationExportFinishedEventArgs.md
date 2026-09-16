# AnimationExportFinishedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.AnimationExportFinishedEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Mapping.Events.AnimationExportFinishedEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class AnimationExportFinishedEventArgs : EventArgs
```


## Members

### ErrorMessage

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.AnimationExportFinishedEventArgs.yml" sourcestartlinenumber="1">Gets the error message if the export failed.</p>


```csharp
public string ErrorMessage { get; }
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.AnimationExportFinishedEventArgs.yml" sourcestartlinenumber="1">Gets the file path for video exports or the folder path for image exports.</p>


```csharp
public string Path { get; }
```
### View

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Events.AnimationExportFinishedEventArgs.yml" sourcestartlinenumber="1">Gets the view used for the export.</p>


```csharp
public MapView View { get; }
```


