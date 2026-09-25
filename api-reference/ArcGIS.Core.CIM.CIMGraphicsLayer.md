# CIMGraphicsLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Represents a layer of simple graphic elements.</p>


## Object Signature

```csharp
public class CIMGraphicsLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGraphicsLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Represents a layer of simple graphic elements.</p>


```csharp
public CIMGraphicsLayer()
```
### BarrierWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Gets or sets the weight of graphics in this layer when considered as barriers to labeling.</p>


```csharp
public BarrierWeight BarrierWeight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGraphicsLayer.</p>


```csharp
public CIMGraphicsLayer Clone()
```
### ElementStorageURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Gets or sets the URI of the storage for the graphic elements themselves.</p>


```csharp
public string ElementStorageURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMGraphicsLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGraphicsLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### InvisibleGraphicsColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Gets or sets the color of invisible graphics.</p>


```csharp
public CIMColor InvisibleGraphicsColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Gets or sets the graphics' reference scale.</p>


```csharp
public double ReferenceScale { get; set; }
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### ShowInvisibleGraphics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer should show invisible graphics.</p>


```csharp
public bool ShowInvisibleGraphics { get; set; }
```
### Snappable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer participates in snapping.</p>


```csharp
public bool Snappable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGraphicsLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicsLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


