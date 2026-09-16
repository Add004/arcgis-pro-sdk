# CIMFloodSimulationBarrier

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation barrier.</p>


## Object Signature

```csharp
public class CIMFloodSimulationBarrier : CIMFloodSimulationObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationBarrier()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation barrier.</p>


```csharp
public CIMFloodSimulationBarrier()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloodSimulationBarrier.</p>


```csharp
public CIMFloodSimulationBarrier Clone()
```
### DensifyPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to add vertices to the path to better follow the terrain.</p>


```csharp
public bool DensifyPath { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Reconstructs the CIMFloodSimulationBarrier with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloodSimulationBarrier FromJson(string json, JsonDeserializationSettings settings = null)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Gets or sets the height of the barrier.</p>


```csharp
public double Height { get; set; }
```
### Path

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Gets or sets the geometry of the barrier.</p>


```csharp
public Polyline Path { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloodSimulationBarrier and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Unit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Gets or sets the unit for the height and width of the barrier. It defaults to meter if left unset.</p>


```csharp
public LinearUnit Unit { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Gets or sets the width of the barrier.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationBarrier.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


