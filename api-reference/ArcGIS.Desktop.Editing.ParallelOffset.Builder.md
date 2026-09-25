# ParallelOffset.Builder

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Defines the parameters used to create a parallel offset from line features.</p>


## Object Signature

```csharp
public sealed class ParallelOffset.Builder
```


## Members

### Builder()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Editing.ParallelOffset.Builder" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public Builder()
```
### AlignConnected

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets If two or more connected lines should have their direction temporarily aligned for the purposes of the copy. (Default value = false)</p>


```csharp
public bool AlignConnected { get; set; }
```
### Build()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Creates a ParallelOffset from the current ParallelOffset.Builder,
for use in <xref href="ArcGIS.Desktop.Editing.EditOperation.Create(ArcGIS.Desktop.Editing.ParallelOffset)?text=EditOperation.Create" data-throw-if-not-resolved="false"></xref></p>


```csharp
public ParallelOffset Build()
```
### CopyToSeparateFeatures

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets if connected lines should be copied to separate lines. (Default value = false).</p>


```csharp
public bool CopyToSeparateFeatures { get; set; }
```
### Corner

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets the shape of corners created in the copied lines. (Default value = ParallelOffset.CornerType.Mitered)</p>


```csharp
public ParallelOffset.CornerType Corner { get; set; }
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets the offset distance in map units. (Default value = 0)</p>


```csharp
public double Distance { get; set; }
```
### Iterations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets the number of parallel offset copies to create. (Default value = 1)</p>


```csharp
public int Iterations { get; set; }
```
### RemoveSelfIntersectingLoops

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets if self intersecting loops should be removed in the copied features. (Default value = True)</p>


```csharp
public bool RemoveSelfIntersectingLoops { get; set; }
```
### Selection

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets the lines to be copied from.</p>


```csharp
public SelectionSet Selection { get; set; }
```
### Side

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets on which side of selected lines the offset lines will be copied. (Default value = ParallelOffset.SideType.Both)</p>


```csharp
public ParallelOffset.SideType Side { get; set; }
```
### Template

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.ParallelOffset.Builder.yml" sourcestartlinenumber="1">Gets and sets the template to create the copies in.</p>


```csharp
public EditingTemplate Template { get; set; }
```


