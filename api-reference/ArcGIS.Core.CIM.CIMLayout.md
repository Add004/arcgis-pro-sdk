# CIMLayout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Represents a layout in a project.</p>


## Object Signature

```csharp
public class CIMLayout : CIMDefinition, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p>
    A layout is a collection of visual elements arranged on a logical sheet of paper. A layout in a GIS is typically used to display one or more maps at a particular extent and scale. The layout is used to compose a presentation of data, describe the maps, and/or tell a story of the map data.
    </p>
<p>
    A layout defines a logical sheet of paper. It has a height and a width, and also a linear unit used to display positions on the page. It can have a snapping grid and a set of guides to help users arrange its elements.
    </p>
<p>
    The layout contains an ordered list of elements. When the layout draws, it tells each element to draw, in order.
    </p>


## Members

### CIMLayout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Represents a layout in a project.</p>


```csharp
public CIMLayout()
```
### CMYKColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the name of the CMYK color profile for a layout.</p>


```csharp
public string CMYKColorProfile { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayout.</p>


```csharp
public CIMLayout Clone()
```
### ColorModel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the color model for a layout.</p>


```csharp
public ColorModel ColorModel { get; set; }
```
### CustomProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the custom properties of the layout. Custom properties are limited to key / value pairs of strings and developers are fully responsible for stored content.</p>


```csharp
public CIMStringMap[] CustomProperties { get; set; }
```
### DateExported

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the date exported property for a layout.</p>


```csharp
public TimeInstant DateExported { get; set; }
```
### DatePrinted

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the date printed property for a layout.</p>


```csharp
public TimeInstant DatePrinted { get; set; }
```
### DefaultColorVisionDeficiencyMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the color vision deficiency mode that new views of this layout are opened with.</p>


```csharp
public ColorVisionDeficiencyType DefaultColorVisionDeficiencyMode { get; set; }
```
### Elements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets a collection of elements.</p>


```csharp
public CIMElement[] Elements { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Reconstructs the CIMLayout with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayout FromJson(string json, JsonDeserializationSettings settings = null)
```
### MapSeries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the map series for a layout.</p>


```csharp
public CIMMapSeries MapSeries { get; set; }
```
### PDFAccessibilityReadingOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the ordered list of element names that defines the reading order for assistive technologies such as screen readers.</p>


```csharp
public string[] PDFAccessibilityReadingOrder { get; set; }
```
### Page

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the CIMPage for the layout.</p>


```csharp
public CIMPage Page { get; set; }
```
### RGBColorProfile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets the name of the RGB color profile for a layout.</p>


```csharp
public string RGBColorProfile { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SimulateOverprint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to simulate overprint for a layout.</p>


```csharp
public bool SimulateOverprint { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


