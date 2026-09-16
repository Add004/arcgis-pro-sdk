# CIMSymbolLayerMasking

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Represents symbol layer masking.</p>


## Object Signature

```csharp
public class CIMSymbolLayerMasking : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSymbolLayerMasking()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Represents symbol layer masking.</p>


```csharp
public CIMSymbolLayerMasking()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolLayerMasking.</p>


```csharp
public CIMSymbolLayerMasking Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolLayerMasking with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolLayerMasking FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SymbolLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Gets or sets the symbol layer identifiers.</p>


```csharp
public CIMSymbolLayerIdentifier[] SymbolLayers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolLayerMasking and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerMasking.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


