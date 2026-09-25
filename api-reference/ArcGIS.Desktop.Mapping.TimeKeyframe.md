# TimeKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeKeyframe.yml" sourcestartlinenumber="1">Represents a keyframe in the <xref href="ArcGIS.Desktop.Mapping.TimeTrack" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class TimeKeyframe : Keyframe
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeKeyframe.yml" sourcestartlinenumber="1">The time keyframe stores the time extent and defines the transitions for the start and end value in the time extent.</p>


## Members

### EndTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeKeyframe.yml" sourcestartlinenumber="1">Gets the method of transition for the end value of the time extent.</p>


```csharp
public AnimationTransition EndTransition { get; set; }
```
### ExcludeEnd

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeKeyframe.yml" sourcestartlinenumber="1">Gets or sets whether times equal to the end time are considered matches.</p>


```csharp
public bool ExcludeEnd { get; set; }
```
### ExcludeStart

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeKeyframe.yml" sourcestartlinenumber="1">Gets or sets whether times equal to the start time are considered matches.</p>


```csharp
public bool ExcludeStart { get; set; }
```
### StartTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the start value of the time extent.</p>


```csharp
public AnimationTransition StartTransition { get; set; }
```
### Time

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.TimeKeyframe.yml" sourcestartlinenumber="1">Gets or sets the value of the time extent.</p>


```csharp
public TimeRange Time { get; set; }
```


