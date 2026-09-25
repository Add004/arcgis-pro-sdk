# CIMKeyframeGeometryStorage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Represents storage for keyframe geometry objects.</p>


## Object Signature

```csharp
public class CIMKeyframeGeometryStorage : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKeyframeGeometryStorage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Represents storage for keyframe geometry objects.</p>


```csharp
public CIMKeyframeGeometryStorage()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeGeometryStorage.</p>


```csharp
public CIMKeyframeGeometryStorage Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeGeometryStorage with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeGeometryStorage FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometryTracks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Gets or sets an array of geometry tracks.</p>


```csharp
public CIMAnimationGeometryTrack[] GeometryTracks { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeGeometryStorage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeGeometryStorage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


