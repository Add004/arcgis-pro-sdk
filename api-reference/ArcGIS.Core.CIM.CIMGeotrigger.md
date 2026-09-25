# CIMGeotrigger

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Represents common properties for all the geotrigger types.</p>


## Object Signature

```csharp
public class CIMGeotrigger : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeotrigger()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Represents common properties for all the geotrigger types.</p>


```csharp
public CIMGeotrigger()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeotrigger.</p>


```csharp
public CIMGeotrigger Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Reconstructs the CIMGeotrigger with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeotrigger FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeotrigger and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotrigger.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


