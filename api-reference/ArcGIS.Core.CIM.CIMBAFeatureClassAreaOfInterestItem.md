# CIMBAFeatureClassAreaOfInterestItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer feature class based area of interest item.</p>


## Object Signature

```csharp
public class CIMBAFeatureClassAreaOfInterestItem : CIMBAAreaOfInterestItem, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAFeatureClassAreaOfInterestItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer feature class based area of interest item.</p>


```csharp
public CIMBAFeatureClassAreaOfInterestItem()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAFeatureClassAreaOfInterestItem.</p>


```csharp
public CIMBAFeatureClassAreaOfInterestItem Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Gets or sets the feature class data connection.</p>


```csharp
public CIMStandardDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Reconstructs the CIMBAFeatureClassAreaOfInterestItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAFeatureClassAreaOfInterestItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAFeatureClassAreaOfInterestItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFeatureClassAreaOfInterestItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


