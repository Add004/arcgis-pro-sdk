# ParallelOffset

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Defines the parameters used to create a parallel offset from line features.</p>


## Object Signature

```csharp
public class ParallelOffset
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">To use ParallelOffset in <xref href="ArcGIS.Desktop.Editing.EditOperation.Create(ArcGIS.Desktop.Editing.ParallelOffset)?text=EditOperation.Create" data-throw-if-not-resolved="false"></xref>,
instantiate a <xref href="ArcGIS.Desktop.Editing.ParallelOffset.Builder?text=ParallelOffset.Builder" data-throw-if-not-resolved="false"></xref>, set the parameters
then call <xref href="ArcGIS.Desktop.Editing.ParallelOffset.Builder.Build" data-throw-if-not-resolved="false"></xref> to return a ParallelOffset.</p>


## Members

### AlignConnected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets If two or more connected lines should have their direction temporarily aligned for the purposes of the copy. (Default value = false)</p>


```csharp
public bool AlignConnected { get; }
```
### CopyToSeparateFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets if connected lines should be copied to separate lines. (Default value = false).</p>


```csharp
public bool CopyToSeparateFeatures { get; }
```
### Corner

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets the shape of corners created in the copied lines. (Default value = ParallelOffset.CornerType.Mitered)</p>


```csharp
public ParallelOffset.CornerType Corner { get; }
```
### Create(Builder)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">A class representing the parameters for copying parallel line features.</p>


```csharp
public static ParallelOffset Create(ParallelOffset.Builder builder)
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets the offset distance in map units. (Default value = 0)</p>


```csharp
public double Distance { get; }
```
### Iterations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets the number of parallel offset copies to create. (Default value = 1)</p>


```csharp
public int Iterations { get; }
```
### RemoveSelfIntersectingLoops

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets if self intersecting loops should be removed in the copied features. (Default value = True)</p>


```csharp
public bool RemoveSelfIntersectingLoops { get; }
```
### Selection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets the lines to be copied from.</p>


```csharp
public SelectionSet Selection { get; }
```
### Side

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Gets on which side of selected lines the offset lines will be copied. (Default value = ParallelOffset.SideType.Both)</p>


```csharp
public ParallelOffset.SideType Side { get; }
```
### ToBuilder()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.yml" sourcestartlinenumber="1">Returns a ParallelOffset.Builder from the current ParallelOffset.</p>


```csharp
public ParallelOffset.Builder ToBuilder()
```


