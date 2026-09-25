# CIMTopoNorthArrow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Represents a topographic north arrow which displays declination of true, grid and magnetic north.</p>


## Object Signature

```csharp
public class CIMTopoNorthArrow : CIMNorthArrow, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTopoNorthArrow()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Represents a topographic north arrow which displays declination of true, grid and magnetic north.</p>


```csharp
public CIMTopoNorthArrow()
```
### AutoUpdate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the properties of the topographic north arrow should update automatically based on changes in the map.</p>


```csharp
public bool AutoUpdate { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTopoNorthArrow.</p>


```csharp
public CIMTopoNorthArrow Clone()
```
### Date

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the date used when calculating declination using world magnetic model.</p>


```csharp
public TimeInstant Date { get; set; }
```
### DateInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating the date interval used to calculate declination. The default value is 5 which is based on the interval used by the World Magnetic Model. A value of zero indicates the current date should be used.</p>


```csharp
public int DateInterval { get; set; }
```
### DeclinationArcSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the line symbol used to display declination arc lines.</p>


```csharp
public CIMSymbolReference DeclinationArcSymbol { get; set; }
```
### DirectionalNotes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the directional notes are displayed on the north arrow.</p>


```csharp
public bool DirectionalNotes { get; set; }
```
### DrawToSpecification

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the element to specification size or allow user to manually resize element.</p>


```csharp
public bool DrawToSpecification { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Reconstructs the CIMTopoNorthArrow with a specified state from a JSON encoding.</p>


```csharp
public static CIMTopoNorthArrow FromJson(string json, JsonDeserializationSettings settings = null)
```
### GMAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the Grid Magnetic declination.</p>


```csharp
public CIMDeclination GMAngle { get; set; }
```
### GridConvergence

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the Grid Convergence declination.</p>


```csharp
public CIMDeclination GridConvergence { get; set; }
```
### GridLinesLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the path to the layer containing the grid lines aligned with the calculated angles.</p>


```csharp
public string GridLinesLayerURI { get; set; }
```
### IsPrimaryZone

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the zone is the primary zone. Set to false when using 2nd north arrow for maps that extend across two UTM zones.</p>


```csharp
public bool IsPrimaryZone { get; set; }
```
### LargeSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the topographic north arrow is displayed in large size.</p>


```csharp
public bool LargeSize { get; set; }
```
### LeadingZero

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether a leading zero is displayed for minute coordinates of grid convergence.</p>


```csharp
public bool LeadingZero { get; set; }
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the symbol used for line elements in the topographic north arrow.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### MagneticNorthNegativeSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the symbol displayed at top of magnetic north line when the gm-angle is negative.</p>


```csharp
public CIMSymbolReference MagneticNorthNegativeSymbol { get; set; }
```
### MagneticNorthPositiveSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the symbol displayed at top of magnetic north line when the gm-angle is positive.</p>


```csharp
public CIMSymbolReference MagneticNorthPositiveSymbol { get; set; }
```
### MagneticNorthZeroSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the symbol displayed at top of magnetic north line when the gm-angle is 0 degrees.</p>


```csharp
public CIMSymbolReference MagneticNorthZeroSymbol { get; set; }
```
### ProductSpecification

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the map product specification type of topographic north arrow.</p>


```csharp
public MapProductSpecType ProductSpecification { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RoundGMAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether GM angle is rounded for display. If true GM angle is displayed to nearest 1/2 degree, if false it is displayed as degrees and minutes.</p>


```csharp
public bool RoundGMAngle { get; set; }
```
### RoundMils

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether Mils rounded for display. If true Mils for both GC and GM will be displayed rounded to nearest 10 Mils, otherwise to nearest 1 Mil.
If RoundGMAngle is true, this property is ignored.</p>


```csharp
public bool RoundMils { get; set; }
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the symbol used for text elements in topographic north arrow.</p>


```csharp
public CIMSymbolReference TextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTopoNorthArrow and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrueNorthMarkerSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the symbol displayed at top of true north line, default is a star.</p>


```csharp
public CIMSymbolReference TrueNorthMarkerSymbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### Zone

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the spatial reference used for calculating declination, typically a UTM zone.</p>


```csharp
public SpatialReference Zone { get; set; }
```


