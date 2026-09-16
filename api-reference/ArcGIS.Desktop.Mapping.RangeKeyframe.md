# RangeKeyframe

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeKeyframe.yml" sourcestartlinenumber="1">Represents a keyframe in the <xref href="ArcGIS.Desktop.Mapping.RangeTrack" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class RangeKeyframe : Keyframe
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeKeyframe.yml" sourcestartlinenumber="1">The range keyframe stores the map range and defines the transitions for the min and max value in the range.</p>


## Members

### IsExclusion

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeKeyframe.yml" sourcestartlinenumber="1">Gets or sets a value indicating if the values between the range are excluded or included.</p>


```csharp
public bool IsExclusion { get; set; }
```
### MaxTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the maximum value of the range.</p>


```csharp
public AnimationTransition MaxTransition { get; set; }
```
### MinTransition

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeKeyframe.yml" sourcestartlinenumber="1">Gets or sets the method of transition for the minimum value of the range.</p>


```csharp
public AnimationTransition MinTransition { get; set; }
```
### Range

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RangeKeyframe.yml" sourcestartlinenumber="1">Gets or sets the value of the range.</p>


```csharp
public Range Range { get; set; }
```


