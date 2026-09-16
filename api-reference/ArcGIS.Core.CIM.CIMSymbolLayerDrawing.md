# CIMSymbolLayerDrawing

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Represents symbol layer drawing properties.</p>


## Object Signature

```csharp
public class CIMSymbolLayerDrawing : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSymbolLayerDrawing()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Represents symbol layer drawing properties.</p>


```csharp
public CIMSymbolLayerDrawing()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSymbolLayerDrawing.</p>


```csharp
public CIMSymbolLayerDrawing Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Reconstructs the CIMSymbolLayerDrawing with a specified state from a JSON encoding.</p>


```csharp
public static CIMSymbolLayerDrawing FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SymbolLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Gets or sets the symbol layer identifiers.</p>


```csharp
public CIMSymbolLayerIdentifier[] SymbolLayers { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSymbolLayerDrawing and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSymbolLayerDrawing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether symbol layer drawing is enabled.</p>


```csharp
public bool UseSymbolLayerDrawing { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSymbolLayerDrawing.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


