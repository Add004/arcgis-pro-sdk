# CIMDoubleFillScaleBar

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Represents a double filled alternating scale bar.</p>


## Object Signature

```csharp
public class CIMDoubleFillScaleBar : CIMScaleBar, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDoubleFillScaleBar()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Represents a double filled alternating scale bar.</p>


```csharp
public CIMDoubleFillScaleBar()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDoubleFillScaleBar.</p>


```csharp
public CIMDoubleFillScaleBar Clone()
```
### FillSymbol1

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Gets or sets the first symbol of an alternating scale bar.</p>


```csharp
public CIMSymbolReference FillSymbol1 { get; set; }
```
### FillSymbol2

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Gets or sets the second symbol of an alternating scale bar.</p>


```csharp
public CIMSymbolReference FillSymbol2 { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Reconstructs the CIMDoubleFillScaleBar with a specified state from a JSON encoding.</p>


```csharp
public static CIMDoubleFillScaleBar FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Style

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Gets or sets the style for the scale bar.</p>


```csharp
public DoubleFillScaleBarStyle Style { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDoubleFillScaleBar and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDoubleFillScaleBar.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


