# CIMLeaderLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Represents a leader line.</p>


## Object Signature

```csharp
public class CIMLeaderLine : CIMLeader, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLeaderLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Represents a leader line.</p>


```csharp
public CIMLeaderLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLeaderLine.</p>


```csharp
public CIMLeaderLine Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Reconstructs the CIMLeaderLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMLeaderLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### Line

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Gets or sets the leader line drawn from the graphic.</p>


```csharp
public Polyline Line { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLeaderLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


