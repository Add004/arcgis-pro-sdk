# CIMChartLineSymbolProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Provides access to members that control properties of the line
symbol.</p>


## Object Signature

```csharp
public class CIMChartLineSymbolProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartLineSymbolProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Provides access to members that control properties of the line
symbol.</p>


```csharp
public CIMChartLineSymbolProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartLineSymbolProperties.</p>


```csharp
public CIMChartLineSymbolProperties Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the color of the line.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMChartLineSymbolProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartLineSymbolProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Style

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the style of the line.</p>


```csharp
public ChartLineDashStyle Style { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartLineSymbolProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the line is visible.</p>


```csharp
public bool Visible { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the width of the line. Units in pixels.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartLineSymbolProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


