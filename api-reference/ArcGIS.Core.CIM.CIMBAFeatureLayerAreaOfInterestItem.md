# CIMBAFeatureLayerAreaOfInterestItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer feature layer based area of interest item.</p>


## Object Signature

```csharp
public class CIMBAFeatureLayerAreaOfInterestItem : CIMBAAreaOfInterestItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAFeatureLayerAreaOfInterestItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer feature layer based area of interest item.</p>


```csharp
public CIMBAFeatureLayerAreaOfInterestItem()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAFeatureLayerAreaOfInterestItem.</p>


```csharp
public CIMBAFeatureLayerAreaOfInterestItem Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Reconstructs the CIMBAFeatureLayerAreaOfInterestItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAFeatureLayerAreaOfInterestItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAFeatureLayerAreaOfInterestItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Gets or sets the area of interest feature layer URI.</p>


```csharp
public string URI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureLayerAreaOfInterestItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


