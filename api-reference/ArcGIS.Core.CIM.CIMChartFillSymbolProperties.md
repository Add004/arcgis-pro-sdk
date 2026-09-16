# CIMChartFillSymbolProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Provides access to members that control properties of the fill
symbol.</p>


## Object Signature

```csharp
public class CIMChartFillSymbolProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartFillSymbolProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Provides access to members that control properties of the fill
symbol.</p>


```csharp
public CIMChartFillSymbolProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartFillSymbolProperties.</p>


```csharp
public CIMChartFillSymbolProperties Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the color of the fill.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMChartFillSymbolProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartFillSymbolProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the properties of the fill symbol border.</p>


```csharp
public CIMChartLineSymbolProperties LineSymbolProperties { get; set; }
```
### Opacity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the transparency level of histogram bars.</p>


```csharp
public int Opacity { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartFillSymbolProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the fill is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartFillSymbolProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


