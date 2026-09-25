# CIMCruisingAltitudeDiagram

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Represents a Cruising Altitude Diagram.</p>


## Object Signature

```csharp
public class CIMCruisingAltitudeDiagram : CIMFrameElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCruisingAltitudeDiagram()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Represents a Cruising Altitude Diagram.</p>


```csharp
public CIMCruisingAltitudeDiagram()
```
### AltitudeTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text symbol used for the altitude values on the diagram.</p>


```csharp
public CIMSymbolReference AltitudeTextSymbol { get; set; }
```
### AutoResizeText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to auto resize the text.</p>


```csharp
public bool AutoResizeText { get; set; }
```
### BearingArrowLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the line symbol used for the arrow that leads from the starting bearing to the ending bearing for a part of the diagram.</p>


```csharp
public CIMSymbolReference BearingArrowLineSymbol { get; set; }
```
### BearingTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text symbol used for the bearing values for each part of the diagram.</p>


```csharp
public CIMSymbolReference BearingTextSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCruisingAltitudeDiagram.</p>


```csharp
public CIMCruisingAltitudeDiagram Clone()
```
### DiagramDiameter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the diameter of the cruising altitude diagram in page units.</p>


```csharp
public double DiagramDiameter { get; set; }
```
### DiagramTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the diagram title.</p>


```csharp
public string DiagramTitle { get; set; }
```
### DiagramType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the diagram type which should be created.</p>


```csharp
public CruisingAltitudeDiagramType DiagramType { get; set; }
```
### DiameterUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the page units used to determine the diameter of the cruising altitude diagram.</p>


```csharp
public LinearUnit DiameterUnits { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Reconstructs the CIMCruisingAltitudeDiagram with a specified state from a JSON encoding.</p>


```csharp
public static CIMCruisingAltitudeDiagram FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalBottomText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the bottom of the horizontal diagram.</p>


```csharp
public string HorizontalBottomText { get; set; }
```
### HorizontalTopText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the top of the horizontal diagram.</p>


```csharp
public string HorizontalTopText { get; set; }
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the line symbol used for the outline of the circle sections on the diagram.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### QuadrantalBottomLeftText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the bottom left of the quadrantal diagram.</p>


```csharp
public string QuadrantalBottomLeftText { get; set; }
```
### QuadrantalBottomRightText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the bottom right of the quadrantal diagram.</p>


```csharp
public string QuadrantalBottomRightText { get; set; }
```
### QuadrantalTopLeftText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the top left of the quadrantal diagram.</p>


```csharp
public string QuadrantalTopLeftText { get; set; }
```
### QuadrantalTopRightText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the top right of the quadrantal diagram.</p>


```csharp
public string QuadrantalTopRightText { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TitleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text symbol used for the diagram title, which appears above the element.</p>


```csharp
public CIMSymbolReference TitleTextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCruisingAltitudeDiagram and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalLeftText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the left side of the vertical diagram.</p>


```csharp
public string VerticalLeftText { get; set; }
```
### VerticalRightText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Gets or sets the text for the right side of the vertical diagram.</p>


```csharp
public string VerticalRightText { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCruisingAltitudeDiagram.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


