# CIMSpatialMapSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Spatial Map Series is a means to create a series of map pages based /// off of spatial features.</p>


## Object Signature

```csharp
public class CIMSpatialMapSeries : CIMMapSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSpatialMapSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Spatial Map Series is a means to create a series of map pages based /// off of spatial features.</p>


```csharp
public CIMSpatialMapSeries()
```
### CategoryField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the category of the page.</p>


```csharp
public string CategoryField { get; set; }
```
### ClipMapToIndexFeature

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether map clipping is synchronized with the current series index feature.</p>


```csharp
public bool ClipMapToIndexFeature { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSpatialMapSeries.</p>


```csharp
public CIMSpatialMapSeries Clone()
```
### ExtentOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the extent fitting options.</p>


```csharp
public ExtentFitType ExtentOptions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMSpatialMapSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMSpatialMapSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### IndexLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the URI of the index layer.</p>


```csharp
public string IndexLayerURI { get; set; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the value of the margin.</p>


```csharp
public double Margin { get; set; }
```
### MarginType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the type of margins.</p>


```csharp
public UnitType MarginType { get; set; }
```
### MarginUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the units of the margin.</p>


```csharp
public LinearUnit MarginUnits { get; set; }
```
### NameField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the name of the specified page.</p>


```csharp
public string NameField { get; set; }
```
### NumberField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the number of the specified page.</p>


```csharp
public string NumberField { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the page specific rotation.</p>


```csharp
public string RotationField { get; set; }
```
### ScaleField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets field that specifies the page specific scale.</p>


```csharp
public string ScaleField { get; set; }
```
### ScaleRounding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the specified value to which the scale rounds to.</p>


```csharp
public double ScaleRounding { get; set; }
```
### SortAscending

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to sort in ascending or descending order.</p>


```csharp
public bool SortAscending { get; set; }
```
### SortField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the required field that specifies the field used to determine /// sort order.</p>


```csharp
public string SortField { get; set; }
```
### SpatialReferenceField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Gets or sets the spatial reference of the page.</p>


```csharp
public string SpatialReferenceField { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSpatialMapSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpatialMapSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


