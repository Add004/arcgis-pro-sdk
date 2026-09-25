# CIMRasterFlowColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Represents a raster flow colorizer that renders animated streamlines for Vector-UV and Vector-MagDir raster sources.</p>


## Object Signature

```csharp
public class CIMRasterFlowColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterFlowColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Represents a raster flow colorizer that renders animated streamlines for Vector-UV and Vector-MagDir raster sources.</p>


```csharp
public CIMRasterFlowColorizer()
```
### AuthoringInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the authoring info. Stores UI authoring metadata used by clients to restore their state when reopening the renderer.</p>


```csharp
public CIMFlowColorizerAuthoringInfo AuthoringInfo { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterFlowColorizer.</p>


```csharp
public CIMRasterFlowColorizer Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the single streamline color used when no color visual variable is active. Default is white.</p>


```csharp
public CIMColor Color { get; set; }
```
### Density

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the density of the streamlines. Controls how many streamlines are seeded.
Values above 1 increase density, values between 0 and 1 decrease it, and a value of 0 shows no streamlines. Very high values may be limited by screen size and trail length.</p>


```csharp
public double Density { get; set; }
```
### DirectionBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the direction band index. When <xref href="ArcGIS.Core.CIM.CIMRasterFlowColorizer.IsUVComponents" data-throw-if-not-resolved="false"></xref> is true, this is the V-component band index.</p>


```csharp
public int DirectionBandIndex { get; set; }
```
### FlowRepresentation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the flow representation type indicating whether data is interpreted as flow-from or flow-to.</p>


```csharp
public FlowRepresentationType FlowRepresentation { get; set; }
```
### FlowSpeed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the flow speed multiplier. Multiplies animation speed without changing trail length. A value of 0 stops animation.</p>


```csharp
public double FlowSpeed { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterFlowColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterFlowColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsUVComponents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether flow is composed from U and V components.</p>


```csharp
public bool IsUVComponents { get; set; }
```
### MagnitudeBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the magnitude band index. When <xref href="ArcGIS.Core.CIM.CIMRasterFlowColorizer.IsUVComponents" data-throw-if-not-resolved="false"></xref> is true, this is the U-component band index.</p>


```csharp
public int MagnitudeBandIndex { get; set; }
```
### MaxPathLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the maximum path length in points. Controls how far a trail can travel before looping.</p>


```csharp
public double MaxPathLength { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the reference system for symbol rotation.</p>


```csharp
public SymbolRotationType ReferenceSystem { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterFlowColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrailCap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the trail cap style. Round only applies when TrailWidth is greater than 3pt. Square is not applicable.</p>


```csharp
public LineCapStyle TrailCap { get; set; }
```
### TrailLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the trail length in points. Controls the visible lit portion of the streamline.
This will be longer where the particle is moving faster, and shorter where the particle is moving slower.</p>


```csharp
public double TrailLength { get; set; }
```
### TrailWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the trail width in points.</p>


```csharp
public double TrailWidth { get; set; }
```
### UseColorVisualVariable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the color visual variable in VisualVariables is active. When false, Color is used instead.</p>


```csharp
public bool UseColorVisualVariable { get; set; }
```
### VisualVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Gets or sets the visual variables. Supports magnitude-driven color, opacity, and size overrides.</p>


```csharp
public CIMVisualVariable[] VisualVariables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterFlowColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


