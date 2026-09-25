# CIMAnimationSymbol

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Provides access to properties of an animation symbol.</p>


## Object Signature

```csharp
public class CIMAnimationSymbol : CIMAnimationObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationSymbol()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Provides access to properties of an animation symbol.</p>


```csharp
public CIMAnimationSymbol()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationSymbol.</p>


```csharp
public CIMAnimationSymbol Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationSymbol with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationSymbol FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationSymbol and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationSymbol.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


