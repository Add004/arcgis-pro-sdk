# LasPointDisplayFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Filter for display of points in a LAS dataset layer.  See <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.GetDisplayFilter" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Mapping.LasDatasetLayer.SetDisplayFilter(ArcGIS.Desktop.Mapping.LasPointDisplayFilter)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class LasPointDisplayFilter
```


## Members

### LasPointDisplayFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Constructs an instance of <xref href="ArcGIS.Desktop.Mapping.LasPointDisplayFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointDisplayFilter()
```
### ClassCodes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the list of classification codes.  Default value is null.</p>


```csharp
public List<int> ClassCodes { get; set; }
```
### KeyPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the key points flag.  Default value is true.</p>


```csharp
public bool KeyPoints { get; set; }
```
### NotFlagged

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the &quot;not flagged&quot; flag.  Default value is true.</p>


```csharp
public bool NotFlagged { get; set; }
```
### OverlapPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the overlap points flag.  Default value is true.</p>


```csharp
public bool OverlapPoints { get; set; }
```
### Returns

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the list of returns.  Default value is null.</p>


```csharp
public List<LasReturnType> Returns { get; set; }
```
### SurfaceConstraints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the list of surface constraint names.  Default value is null.</p>


```csharp
public List<string> SurfaceConstraints { get; set; }
```
### SyntheticPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the synthetic points flag.  Default value is true.</p>


```csharp
public bool SyntheticPoints { get; set; }
```
### WithheldPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointDisplayFilter.yml" sourcestartlinenumber="1">Gets and sets the withheld points flag.  Default value is false.</p>


```csharp
public bool WithheldPoints { get; set; }
```


