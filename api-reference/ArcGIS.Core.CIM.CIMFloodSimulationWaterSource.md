# CIMFloodSimulationWaterSource

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation water source.</p>


## Object Signature

```csharp
public class CIMFloodSimulationWaterSource : CIMFloodSimulationWaterObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationWaterSource()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation water source.</p>


```csharp
public CIMFloodSimulationWaterSource()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloodSimulationWaterSource.</p>


```csharp
public CIMFloodSimulationWaterSource Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Reconstructs the CIMFloodSimulationWaterSource with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloodSimulationWaterSource FromJson(string json, JsonDeserializationSettings settings = null)
```
### Location

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Gets or sets the location.</p>


```csharp
public MapPoint Location { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloodSimulationWaterSource and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WaterSinkConnections

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Gets or sets an array of water sink connections. Water flows from the connected sinks to this source instead of using a fixed flow rate when set.</p>


```csharp
public CIMFloodSimulationSinkConnection[] WaterSinkConnections { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSource.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


