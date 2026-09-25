# SplitByEqualDistance

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualDistance.yml" sourcestartlinenumber="1">Split By Equal Distance class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class SplitByEqualDistance : SplitMethod
```


## Members

### SplitByEqualDistance()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualDistance.yml" sourcestartlinenumber="1">Create a new Split by Equal Distance object.</p>


```csharp
public SplitByEqualDistance()
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualDistance.yml" sourcestartlinenumber="1">Gets and sets the split distance.</p>


```csharp
public double Distance { get; set; }
```
### ProportionRemainder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualDistance.yml" sourcestartlinenumber="1">Gets and sets the proportion remainder. The remainder will be proportioned equally amonngst the new features. Default value is false.</p>


```csharp
public bool ProportionRemainder { get; set; }
```
### Repetitions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualDistance.yml" sourcestartlinenumber="1">Gets and sets the number of times to split at the specified distance.</p>


```csharp
public int Repetitions { get; set; }
```
### SplitFromStartPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByEqualDistance.yml" sourcestartlinenumber="1">Gets and sets the Split From start Point. Default value is true.</p>


```csharp
public bool SplitFromStartPoint { get; set; }
```


