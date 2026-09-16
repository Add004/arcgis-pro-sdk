# CIMAnimationGeometryStorage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Represents storage for animation geometry objects.</p>


## Object Signature

```csharp
public class CIMAnimationGeometryStorage : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationGeometryStorage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Represents storage for animation geometry objects.</p>


```csharp
public CIMAnimationGeometryStorage()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationGeometryStorage.</p>


```csharp
public CIMAnimationGeometryStorage Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationGeometryStorage with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationGeometryStorage FromJson(string json, JsonDeserializationSettings settings = null)
```
### Geometries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Gets or sets an array of geometries.</p>


```csharp
public CIMAnimationGeometry[] Geometries { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Gets or sets an array of symbols.</p>


```csharp
public CIMAnimationSymbol[] Symbols { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationGeometryStorage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometryStorage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


