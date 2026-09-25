# CIMRasterVectorFieldColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Represents a raster vector field colorizer.</p>


## Object Signature

```csharp
public class CIMRasterVectorFieldColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterVectorFieldColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Represents a raster vector field colorizer.</p>


```csharp
public CIMRasterVectorFieldColorizer()
```
### ClassBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the class breaks.</p>


```csharp
public CIMClassBreak[] ClassBreaks { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterVectorFieldColorizer.</p>


```csharp
public CIMRasterVectorFieldColorizer Clone()
```
### DirectionBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the direction band index.</p>


```csharp
public int DirectionBandIndex { get; set; }
```
### FlowRepresentation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the flow representation type.</p>


```csharp
public FlowRepresentationType FlowRepresentation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterVectorFieldColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterVectorFieldColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### FromUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the from unit.</p>


```csharp
public SpeedUnitType FromUnit { get; set; }
```
### IsUVComponents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether flow is composed from U and V components.</p>


```csharp
public bool IsUVComponents { get; set; }
```
### MagnitudeBandIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the magnitude band index.</p>


```csharp
public int MagnitudeBandIndex { get; set; }
```
### MaximumMagnitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the maximum magnitude.</p>


```csharp
public double MaximumMagnitude { get; set; }
```
### MaximumSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the maximum symbol size.</p>


```csharp
public double MaximumSymbolSize { get; set; }
```
### MinimumClassBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the minimum class break.</p>


```csharp
public double MinimumClassBreak { get; set; }
```
### MinimumMagnitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the minimum magnitude.</p>


```csharp
public double MinimumMagnitude { get; set; }
```
### MinimumSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the minimum symbol size.</p>


```csharp
public double MinimumSymbolSize { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the number format used for format values for display.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceSystem

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the reference system for symbol rotation.</p>


```csharp
public SymbolRotationType ReferenceSystem { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### SymbolTileSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the symbol tile size.</p>


```csharp
public double SymbolTileSize { get; set; }
```
### SymbolTileSizeUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the symbol tile size units.</p>


```csharp
public SymbolTileUnitType SymbolTileSizeUnits { get; set; }
```
### SymbolizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the symbolization type.</p>


```csharp
public SymbolizationType SymbolizationType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterVectorFieldColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Gets or sets the to unit.</p>


```csharp
public SpeedUnitType ToUnit { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterVectorFieldColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


