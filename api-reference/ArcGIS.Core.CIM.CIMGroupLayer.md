# CIMGroupLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Represents a group layer which is a simple ordered collection of other layers.</p>


## Object Signature

```csharp
public class CIMGroupLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGroupLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Represents a group layer which is a simple ordered collection of other layers.</p>


```csharp
public CIMGroupLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGroupLayer.</p>


```csharp
public CIMGroupLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMGroupLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGroupLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Gets or sets the layer URIs of the layers in the group layer.</p>


```csharp
public string[] Layers { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### SublayerVisibilityMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Gets or sets the visibility mode for sublayers.</p>


```csharp
public SublayerVisibilityMode SublayerVisibilityMode { get; set; }
```
### SymbolLayerDrawing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Gets or sets the symbol layer drawing definition.</p>


```csharp
public CIMSymbolLayerDrawing SymbolLayerDrawing { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGroupLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGroupLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


