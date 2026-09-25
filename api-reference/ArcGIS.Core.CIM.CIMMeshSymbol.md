# CIMMeshSymbol

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Represents a mesh symbol which is used to draw multipatch features or mesh features.</p>


## Object Signature

```csharp
public class CIMMeshSymbol : CIMMultiLayerSymbol, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMeshSymbol()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Represents a mesh symbol which is used to draw multipatch features or mesh features.</p>


```csharp
public CIMMeshSymbol()
```
### AnimatedSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Gets or sets the collection of symbol properties that apply when the symbol layer has animation data.</p>


```csharp
public CIMAnimatedSymbolProperties AnimatedSymbolProperties { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMeshSymbol.</p>


```csharp
public CIMMeshSymbol Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Reconstructs the CIMMeshSymbol with a specified state from a JSON encoding.</p>


```csharp
public static CIMMeshSymbol FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMeshSymbol and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMeshSymbol.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


