# TransformationInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Define the transformation information used to populate each row of the table
within the TransformationsControl. All the properties within the TransformationInfo are optional.</p>


## Object Signature

```csharp
public class TransformationInfo
```


## Members

### TransformationInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Define the transformation information used to populate each row of the table
within the TransformationsControl. All the properties within the TransformationInfo are optional.</p>


```csharp
public TransformationInfo()
```
### SourceSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the source spatial reference to be used for the TransformationInfo
object (used to populate a table row).</p>


```csharp
public SpatialReference SourceSpatialReference { get; set; }
```
### SourceVcsWkid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the vertical coordinate system wkid
to be used to select the source spatial reference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public int SourceVcsWkid { get; set; }
```
### SourceVcsWkt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the vertical coordinate system wkt
to be used to select the source spatial reference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public string SourceVcsWkt { get; set; }
```
### SourceWkid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the source spatial reference wkid to be used to select the SourceSpatialReference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public int SourceWkid { get; set; }
```
### SourceWkt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the source spatial reference wkt to be used to select the SourceSpatialReference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public string SourceWkt { get; set; }
```
### SpatialFilter

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the spatial filter. If specified, the SpatialFilter will be used to filter the available transformations for the given source
and target spatial reference (which can initially not be defined).</p>


```csharp
public Envelope SpatialFilter { get; set; }
```
### TargetSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the target spatial reference to be used for the TransformationInfo
object (used to populate a table row).</p>


```csharp
public SpatialReference TargetSpatialReference { get; set; }
```
### TargetVcsWkid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the vertical coordinate system wkid
to be used to select the target spatial reference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public int TargetVcsWkid { get; set; }
```
### TargetVcsWkt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the vertical coordinate system wkt
to be used to select the target spatial reference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public string TargetVcsWkt { get; set; }
```
### TargetWkid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the target spatial reference wkid to be used to select the TargetSpatialReference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public int TargetWkid { get; set; }
```
### TargetWkt

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the target spatial reference wkt to be used to select the TargetSpatialReference for the
TransformationInfo object (used to populate a table row).</p>


```csharp
public string TargetWkt { get; set; }
```
### TransformationName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.TransformationInfo.yml" sourcestartlinenumber="1">Gets and sets the name of the transformation to select for the TransformationInfo
object (used to populate a table row), for example &quot;WGS_1984_(ITRF00)_To_NAD_1983&quot;.</p>


```csharp
public string TransformationName { get; set; }
```


