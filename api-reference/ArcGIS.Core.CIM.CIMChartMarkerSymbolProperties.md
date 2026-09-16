# CIMChartMarkerSymbolProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Provides access to members that control properties of the marker
symbol.</p>


## Object Signature

```csharp
public class CIMChartMarkerSymbolProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartMarkerSymbolProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Provides access to members that control properties of the marker
symbol.</p>


```csharp
public CIMChartMarkerSymbolProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartMarkerSymbolProperties.</p>


```csharp
public CIMChartMarkerSymbolProperties Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the color of the symbol fill.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMChartMarkerSymbolProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartMarkerSymbolProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the height of the symbol. Units in pixels.</p>


```csharp
public double Height { get; set; }
```
### LineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the properties of the symbol border.</p>


```csharp
public CIMChartLineSymbolProperties LineSymbolProperties { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Style

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the style of the symbol.</p>


```csharp
public ChartMarkerSymbolStyle Style { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartMarkerSymbolProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the symbol is visible.</p>


```csharp
public bool Visible { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the width of the symbol. Units in pixels.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMarkerSymbolProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


