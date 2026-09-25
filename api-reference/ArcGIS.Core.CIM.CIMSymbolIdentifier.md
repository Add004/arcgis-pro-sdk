# CIMSymbolIdentifier

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Represents a symbol identifier.</p>


## Object Signature

```csharp
public class CIMSymbolIdentifier : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSymbolIdentifier()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Represents a symbol identifier.</p>


```csharp
public CIMSymbolIdentifier()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolIdentifier.</p>


```csharp
public CIMSymbolIdentifier Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolIdentifier with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolIdentifier FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Gets or sets the ID which identifies the symbol in the collection.</p>


```csharp
public int ID { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Gets or sets the name of the symbol in the symbol collection.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbol Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolIdentifier and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolIdentifier.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


