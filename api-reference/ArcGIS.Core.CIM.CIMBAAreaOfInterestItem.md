# CIMBAAreaOfInterestItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer area of interest item.</p>


## Object Signature

```csharp
public class CIMBAAreaOfInterestItem : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAAreaOfInterestItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer area of interest item.</p>


```csharp
public CIMBAAreaOfInterestItem()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAAreaOfInterestItem.</p>


```csharp
public CIMBAAreaOfInterestItem Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Reconstructs the CIMBAAreaOfInterestItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAAreaOfInterestItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Gets or sets the area of interest item name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAAreaOfInterestItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterestItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


