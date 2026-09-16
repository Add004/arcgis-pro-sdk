# CIMScaleLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Represents a Scale line on a page layout.</p>


## Object Signature

```csharp
public class CIMScaleLine : CIMScaleBar, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMScaleLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Represents a Scale line on a page layout.</p>


```csharp
public CIMScaleLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMScaleLine.</p>


```csharp
public CIMScaleLine Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Reconstructs the CIMScaleLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMScaleLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Gets or sets the scale line symbol.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Stepped

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the scale line should be stepped.</p>


```csharp
public bool Stepped { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMScaleLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScaleLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


