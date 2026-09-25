# CIMSlopeGuide

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">A slope guide surround element which is used to ascertaining terrain slope graphically /// as a percentage and a gradient (degree).</p>


## Object Signature

```csharp
public class CIMSlopeGuide : CIMMapProductSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSlopeGuide()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">A slope guide surround element which is used to ascertaining terrain slope graphically /// as a percentage and a gradient (degree).</p>


```csharp
public CIMSlopeGuide()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSlopeGuide.</p>


```csharp
public CIMSlopeGuide Clone()
```
### ContourInterval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the contour interval.</p>


```csharp
public int ContourInterval { get; set; }
```
### ContourIntervalField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the name of the contour interval field.</p>


```csharp
public string ContourIntervalField { get; set; }
```
### FootnoteTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for footnote at bottom of slope guide.</p>


```csharp
public CIMSymbolReference FootnoteTextSymbol { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Reconstructs the CIMSlopeGuide with a specified state from a JSON encoding.</p>


```csharp
public static CIMSlopeGuide FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for horizontal lines in slope guide.</p>


```csharp
public CIMSymbolReference HorizontalLineSymbol { get; set; }
```
### MapScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the map scale the slope guide will be based on.</p>


```csharp
public int MapScale { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SlopeGuideLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the layer used to calculate slope guide.</p>


```csharp
public string SlopeGuideLayerURI { get; set; }
```
### SlopeTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for labeling slope values.</p>


```csharp
public CIMSymbolReference SlopeTextSymbol { get; set; }
```
### SlopeUnitTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for text identifying slope as percentage or degree.</p>


```csharp
public CIMSymbolReference SlopeUnitTextSymbol { get; set; }
```
### TickLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for dashed lines in slope guide.</p>


```csharp
public CIMSymbolReference TickLineSymbol { get; set; }
```
### TitleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for title of element.</p>


```csharp
public CIMSymbolReference TitleTextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSlopeGuide and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Gets or sets the symbol used for vertical lines in slope guide.</p>


```csharp
public CIMSymbolReference VerticalLineSymbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlopeGuide.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


