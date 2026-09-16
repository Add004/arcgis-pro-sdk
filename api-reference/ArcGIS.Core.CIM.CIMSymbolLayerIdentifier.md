# CIMSymbolLayerIdentifier

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Represents symbol layer identifier.</p>


## Object Signature

```csharp
public class CIMSymbolLayerIdentifier : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSymbolLayerIdentifier()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Represents symbol layer identifier.</p>


```csharp
public CIMSymbolLayerIdentifier()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolLayerIdentifier.</p>


```csharp
public CIMSymbolLayerIdentifier Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolLayerIdentifier with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolLayerIdentifier FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SymbolLayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Gets or sets the symbol layer name.</p>


```csharp
public string SymbolLayerName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolLayerIdentifier and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerIdentifier.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


