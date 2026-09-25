# CIMOrientedImageryImageAccessConnections

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Represents access information for secured oriented imagery.</p>


## Object Signature

```csharp
public class CIMOrientedImageryImageAccessConnections : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMOrientedImageryImageAccessConnections()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Represents access information for secured oriented imagery.</p>


```csharp
public CIMOrientedImageryImageAccessConnections()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Creates a deep copy of CIMOrientedImageryImageAccessConnections.</p>


```csharp
public CIMOrientedImageryImageAccessConnections Clone()
```
### ConnectionFile

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Gets or sets the path to the connection file used to access the imagery.</p>


```csharp
public string ConnectionFile { get; set; }
```
### ConnectionString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Gets or sets the connection string.</p>


```csharp
public string ConnectionString { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Reconstructs the CIMOrientedImageryImageAccessConnections with a specified state from a JSON encoding.</p>


```csharp
public static CIMOrientedImageryImageAccessConnections FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Gets or sets the identifier for the access information.</p>


```csharp
public string ID { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMOrientedImageryImageAccessConnections and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMOrientedImageryImageAccessConnections.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


