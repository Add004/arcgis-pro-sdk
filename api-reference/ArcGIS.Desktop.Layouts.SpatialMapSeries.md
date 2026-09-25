# SpatialMapSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Represents a series of pages that span a range of map extents based on features in a specified index layer.</p>


## Object Signature

```csharp
public class SpatialMapSeries : MapSeries
```


## Members

### CategoryField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets index layer's category field.</p>


```csharp
public string CategoryField { get; set; }
```
### CurrentRow

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Returns the index layer's row for the current map series page.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Row CurrentRow { get; }
```
### ExtentOptions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the extent fitting options.</p>


```csharp
public ExtentFitType ExtentOptions { get; set; }
```
### IndexLayer

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the index layer for the maps series.</p>


```csharp
public BasicFeatureLayer IndexLayer { get; set; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the value of the margin.</p>


```csharp
public double Margin { get; set; }
```
### MarginType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the type of margins.</p>


```csharp
public UnitType MarginType { get; set; }
```
### MarginUnits

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the units of the margin.</p>


```csharp
public LinearUnit MarginUnits { get; set; }
```
### PageNameField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the index layer's name field which should uniquely identify each page.</p>


```csharp
public string PageNameField { get; set; }
```
### PageNumberField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the index layer's page number field.</p>


```csharp
public string PageNumberField { get; set; }
```
### RotationField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets index layer's rotation field.</p>


```csharp
public string RotationField { get; set; }
```
### ScaleField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets index layer's scale field.</p>


```csharp
public string ScaleField { get; set; }
```
### ScaleRounding

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the specified value to which the scale rounds.</p>


```csharp
public double ScaleRounding { get; set; }
```
### SortAscending

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets if values based on the sort field are in ascending order.</p>


```csharp
public bool SortAscending { get; set; }
```
### SortField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets index layer's sort field.</p>


```csharp
public string SortField { get; set; }
```
### SpatialReferenceField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.SpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets index layer's spatial reference field.</p>


```csharp
public string SpatialReferenceField { get; set; }
```


