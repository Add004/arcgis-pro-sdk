# DisplayUnitFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.UnitFormats.html">UnitFormats</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Provides unit formatting within a Pro project</p>


## Object Signature

```csharp
public class DisplayUnitFormat : PropertyChangedBase
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Supports property notification</p>


## Members

### Abbreviation

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets and sets the abbrevation string of the unit format</p>


```csharp
public string Abbreviation { get; set; }
```
### AngleFormat

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets the AngleFormat used for unit formatting</p>


```csharp
public CIMAngleFormat AngleFormat { get; }
```
### DisplayName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets and sets the display name of the unit format</p>


```csharp
public string DisplayName { get; set; }
```
### DisplayNamePlural

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets and sets the plural form of the display name of the unit format</p>


```csharp
public string DisplayNamePlural { get; set; }
```
### FormatLocation(Coordinate2D, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Format the input location using the location unit format. This method
must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string FormatLocation(Coordinate2D location, SpatialReference sr = null)
```
### FormatLocation(MapPoint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Format the input location using the location unit format. This method
must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string FormatLocation(MapPoint location)
```
### FormatLocation(double, double, SpatialReference)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Format the input location using the location unit format. This method
must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string FormatLocation(double x, double y, SpatialReference sr = null)
```
### FormatValue(double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Format the input value using the unit format. This method
must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string FormatValue(double value)
```
### MeasurementUnit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets the measurement unit used by the unit format</p>


```csharp
public Unit MeasurementUnit { get; }
```
### SetAngleFormat(CIMAngleFormat)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Apply changes to the angle format</p>


```csharp
public void SetAngleFormat(CIMAngleFormat angleFormat)
```
### SetUnitFormat(CIMObject)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Apply changes to the number format</p>


```csharp
public void SetUnitFormat(CIMObject cimFormat)
```
### UnitCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets the factory code of the unit format</p>


```csharp
public int UnitCode { get; }
```
### UnitFormat

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets the format being used for unit formatting.</p>


```csharp
public CIMObject UnitFormat { get; }
```
### UnitFormatType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets the type of unit formatting</p>


```csharp
public UnitFormatType UnitFormatType { get; }
```
### UnitName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.UnitFormats.DisplayUnitFormat.yml" sourcestartlinenumber="1">Gets the name of the unit format</p>


```csharp
public string UnitName { get; }
```


