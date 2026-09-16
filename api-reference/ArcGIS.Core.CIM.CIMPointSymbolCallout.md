# CIMPointSymbolCallout

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Represents a point symbol callout which draws a point symbol as the background and a line symbol for leaders. Often used for highway shields.</p>


## Object Signature

```csharp
public class CIMPointSymbolCallout : CIMLineCallout, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointSymbolCallout()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Represents a point symbol callout which draws a point symbol as the background and a line symbol for leaders. Often used for highway shields.</p>


```csharp
public CIMPointSymbolCallout()
```
### BackgroundScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Gets or sets an enumeration value that defines how the background is scaled to fit the dimensions of the symbol.</p>


```csharp
public PointSymbolCalloutScale BackgroundScale { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPointSymbolCallout.</p>


```csharp
public CIMPointSymbolCallout Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Reconstructs the CIMPointSymbolCallout with a specified state from a JSON encoding.</p>


```csharp
public static CIMPointSymbolCallout FromJson(string json, JsonDeserializationSettings settings = null)
```
### PointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Gets or sets the symbol that will be drawn as the background behind the text. The most common use case for this type of symbol is a highway shield. When drawing a highway shield this property will be the shield itself without numbers.</p>


```csharp
public CIMPointSymbol PointSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPointSymbolCallout and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointSymbolCallout.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


