# CIMFloodSimulationStorage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Represents storage for flood simulation data objects.</p>


## Object Signature

```csharp
public class CIMFloodSimulationStorage : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationStorage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Represents storage for flood simulation data objects.</p>


```csharp
public CIMFloodSimulationStorage()
```
### Barriers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Gets or sets an array of barriers.</p>


```csharp
public CIMFloodSimulationBarrier[] Barriers { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloodSimulationStorage.</p>


```csharp
public CIMFloodSimulationStorage Clone()
```
### Culverts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Gets or sets an array of culverts.</p>


```csharp
public CIMFloodSimulationCulvert[] Culverts { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Reconstructs the CIMFloodSimulationStorage with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloodSimulationStorage FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloodSimulationStorage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WaterSinkAreas

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Gets or sets an array of water sink areas.</p>


```csharp
public CIMFloodSimulationWaterSinkArea[] WaterSinkAreas { get; set; }
```
### WaterSourceAreas

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Gets or sets an array of water source areas.</p>


```csharp
public CIMFloodSimulationWaterSourceArea[] WaterSourceAreas { get; set; }
```
### WaterSources

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Gets or sets an array of water sources.</p>


```csharp
public CIMFloodSimulationWaterSource[] WaterSources { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationStorage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


