# SplitByVaryingDistance

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByVaryingDistance.yml" sourcestartlinenumber="1">Split By Varying Distance class.  Use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Split(ArcGIS.Desktop.Mapping.Layer%2cSystem.Int64%2cArcGIS.Desktop.Editing.SplitMethod)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public sealed class SplitByVaryingDistance : SplitMethod
```


## Members

### SplitByVaryingDistance()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByVaryingDistance.yml" sourcestartlinenumber="1">Create a new Split by Varying Distance object.</p>


```csharp
public SplitByVaryingDistance()
```
### Distances

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByVaryingDistance.yml" sourcestartlinenumber="1">Gets and sets the set of split distances.  Distances are not cumulative.</p>


```csharp
public List<double> Distances { get; set; }
```
### ProportionRemainder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByVaryingDistance.yml" sourcestartlinenumber="1">Gets and sets the proportion remainder. The remainder will be proportioned amonngst the new features according to distances entered. Default value is false.</p>


```csharp
public bool ProportionRemainder { get; set; }
```
### SplitFromStartPoint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.SplitByVaryingDistance.yml" sourcestartlinenumber="1">Gets and sets the Split From start Point. Default value is true.</p>


```csharp
public bool SplitFromStartPoint { get; set; }
```


