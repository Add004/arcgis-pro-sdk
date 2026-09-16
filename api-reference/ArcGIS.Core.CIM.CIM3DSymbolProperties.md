# CIM3DSymbolProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Represents 3D symbol properties, a collection of symbol properties that apply when the symbol is used in a 3D context.</p>


## Object Signature

```csharp
public class CIM3DSymbolProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIM3DSymbolProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Represents 3D symbol properties, a collection of symbol properties that apply when the symbol is used in a 3D context.</p>


```csharp
public CIM3DSymbolProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIM3DSymbolProperties.</p>


```csharp
public CIM3DSymbolProperties Clone()
```
### DominantSizeAxis3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the dominant size axis.</p>


```csharp
public DominantSizeAxis DominantSizeAxis3D { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Reconstructs the CIM3DSymbolProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIM3DSymbolProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotationOrder3D

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the rotation order 3D.</p>


```csharp
public RotationOrder RotationOrder3D { get; set; }
```
### ScaleY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the scale Y.</p>


```csharp
public double ScaleY { get; set; }
```
### ScaleZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Gets or sets the scale Z.</p>


```csharp
public double ScaleZ { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIM3DSymbolProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIM3DSymbolProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


