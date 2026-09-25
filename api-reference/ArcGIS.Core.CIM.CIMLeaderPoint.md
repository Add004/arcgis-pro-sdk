# CIMLeaderPoint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Represents a leader point.</p>


## Object Signature

```csharp
public class CIMLeaderPoint : CIMLeader, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLeaderPoint()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Represents a leader point.</p>


```csharp
public CIMLeaderPoint()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLeaderPoint.</p>


```csharp
public CIMLeaderPoint Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Reconstructs the CIMLeaderPoint with a specified state from a JSON encoding.</p>


```csharp
public static CIMLeaderPoint FromJson(string json, JsonDeserializationSettings settings = null)
```
### Point

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Gets or sets the anchor point for the leader.</p>


```csharp
public MapPoint Point { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLeaderPoint and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLeaderPoint.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


