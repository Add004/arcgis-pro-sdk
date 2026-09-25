# CIMKeyframeElevationSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Represents an elevation source keyframe.</p>


## Object Signature

```csharp
public class CIMKeyframeElevationSource : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKeyframeElevationSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Represents an elevation source keyframe.</p>


```csharp
public CIMKeyframeElevationSource()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKeyframeElevationSource.</p>


```csharp
public CIMKeyframeElevationSource Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Reconstructs the CIMKeyframeElevationSource with a specified state from a JSON encoding.</p>


```csharp
public static CIMKeyframeElevationSource FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Gets or sets the id for the elevation source.</p>


```csharp
public string SourceID { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKeyframeElevationSource and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the elevation source is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKeyframeElevationSource.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


