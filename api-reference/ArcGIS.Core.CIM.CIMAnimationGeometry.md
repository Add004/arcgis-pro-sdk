# CIMAnimationGeometry

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Provides access to properties of an animation geometry.</p>


## Object Signature

```csharp
public class CIMAnimationGeometry : CIMAnimationObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAnimationGeometry()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Provides access to properties of an animation geometry.</p>


```csharp
public CIMAnimationGeometry()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnimationGeometry.</p>


```csharp
public CIMAnimationGeometry Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Reconstructs the CIMAnimationGeometry with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnimationGeometry FromJson(string json, JsonDeserializationSettings settings = null)
```
### Geometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Gets or sets the geometry.</p>


```csharp
public Geometry Geometry { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnimationGeometry and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnimationGeometry.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


