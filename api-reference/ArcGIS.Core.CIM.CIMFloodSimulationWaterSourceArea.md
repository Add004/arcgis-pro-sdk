# CIMFloodSimulationWaterSourceArea

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation water source.</p>


## Object Signature

```csharp
public class CIMFloodSimulationWaterSourceArea : CIMFloodSimulationWaterObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationWaterSourceArea()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation water source.</p>


```csharp
public CIMFloodSimulationWaterSourceArea()
```
### Area

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Gets or sets the area.</p>


```csharp
public Polygon Area { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloodSimulationWaterSourceArea.</p>


```csharp
public CIMFloodSimulationWaterSourceArea Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Reconstructs the CIMFloodSimulationWaterSourceArea with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloodSimulationWaterSourceArea FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloodSimulationWaterSourceArea and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterSourceArea.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


