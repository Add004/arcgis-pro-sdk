# CIMBAStdGeoAreaOfInterestItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer standard geography based area of interest item.</p>


## Object Signature

```csharp
public class CIMBAStdGeoAreaOfInterestItem : CIMBAAreaOfInterestItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAStdGeoAreaOfInterestItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer standard geography based area of interest item.</p>


```csharp
public CIMBAStdGeoAreaOfInterestItem()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAStdGeoAreaOfInterestItem.</p>


```csharp
public CIMBAStdGeoAreaOfInterestItem Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Reconstructs the CIMBAStdGeoAreaOfInterestItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAStdGeoAreaOfInterestItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeographyID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Gets or sets the standard geography geography ID.</p>


```csharp
public string GeographyID { get; set; }
```
### LevelID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Gets or sets the standard geography level ID.</p>


```csharp
public string LevelID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAStdGeoAreaOfInterestItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAStdGeoAreaOfInterestItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


