# CIMBAAreaOfInterest

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer Area Of Interest properties.</p>


## Object Signature

```csharp
public class CIMBAAreaOfInterest : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAAreaOfInterest()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer Area Of Interest properties.</p>


```csharp
public CIMBAAreaOfInterest()
```
### AreaOfInterestDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Gets or sets the area of interest data connection.</p>


```csharp
public CIMStandardDataConnection AreaOfInterestDataConnection { get; set; }
```
### AreaOfInterestItems

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Gets or sets the area of interest items.</p>


```csharp
public CIMBAAreaOfInterestItem[] AreaOfInterestItems { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAAreaOfInterest.</p>


```csharp
public CIMBAAreaOfInterest Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Reconstructs the CIMBAAreaOfInterest with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAAreaOfInterest FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAAreaOfInterest and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAAreaOfInterest.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


