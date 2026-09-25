# CIMTrajectoryLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Represents a trajectory layer corresponding to a trajectory dataset.</p>


## Object Signature

```csharp
public class CIMTrajectoryLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTrajectoryLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Represents a trajectory layer corresponding to a trajectory dataset.</p>


```csharp
public CIMTrajectoryLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTrajectoryLayer.</p>


```csharp
public CIMTrajectoryLayer Clone()
```
### FootprintLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the footprint feature layer.</p>


```csharp
public string FootprintLayer { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTrajectoryLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTrajectoryLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### PointLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Gets or sets the path of the point feature layer.</p>


```csharp
public string PointLayer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTrajectoryLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrajectoryDatasetConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection of the trajectory dataset.</p>


```csharp
public CIMDataConnection TrajectoryDatasetConnection { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTrajectoryLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


