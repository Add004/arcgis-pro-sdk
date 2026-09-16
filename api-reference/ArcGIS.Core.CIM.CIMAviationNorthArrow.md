# CIMAviationNorthArrow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Represents a aviation north arrow which displays declination of true, grid and magnetic north.</p>


## Object Signature

```csharp
public class CIMAviationNorthArrow : CIMNorthArrow, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAviationNorthArrow()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Represents a aviation north arrow which displays declination of true, grid and magnetic north.</p>


```csharp
public CIMAviationNorthArrow()
```
### AutoUpdate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the north arrow auto updates.</p>


```csharp
public bool AutoUpdate { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAviationNorthArrow.</p>


```csharp
public CIMAviationNorthArrow Clone()
```
### Date

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the date used when calculating declination using world magnetic model.</p>


```csharp
public TimeInstant Date { get; set; }
```
### DeclinationSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the spatial reference used for calculating declination, typically a UTM zone.</p>


```csharp
public SpatialReference DeclinationSpatialReference { get; set; }
```
### DisplayRateOfChange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the rate of change text.</p>


```csharp
public bool DisplayRateOfChange { get; set; }
```
### DisplayVariationDate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the variation date.</p>


```csharp
public bool DisplayVariationDate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Reconstructs the CIMAviationNorthArrow with a specified state from a JSON encoding.</p>


```csharp
public static CIMAviationNorthArrow FromJson(string json, JsonDeserializationSettings settings = null)
```
### GMAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the Grid Magnetic declination.</p>


```csharp
public CIMDeclination GMAngle { get; set; }
```
### GridConvergence

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the Grid Convergence declination.</p>


```csharp
public CIMDeclination GridConvergence { get; set; }
```
### GridNorthArrow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the grid north arrow for the aviation north arrow.</p>


```csharp
public CIMAviationArrow GridNorthArrow { get; set; }
```
### MagneticNorthArrow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the magnetic north arrow for the aviation north arrow.</p>


```csharp
public CIMAviationArrow MagneticNorthArrow { get; set; }
```
### RateOfChangeText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the rate of change text displayed.</p>


```csharp
public string RateOfChangeText { get; set; }
```
### RateOfChangeTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the rate of change text symbol for the north arrow.</p>


```csharp
public CIMSymbolReference RateOfChangeTextSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAviationNorthArrow and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrueNorthArrow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the true north arrow for aviation north arrow.</p>


```csharp
public CIMAviationArrow TrueNorthArrow { get; set; }
```
### Variation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the variation for the aviation north arrow.</p>


```csharp
public CIMAviationVariation Variation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAviationNorthArrow.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


