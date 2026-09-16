# CIMBinningVisualization

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Describes the appearance and application behavior of polygon aggregation bins.</p>


## Object Signature

```csharp
public class CIMBinningVisualization : CIMAggregateVisualization, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBinningVisualization()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Describes the appearance and application behavior of polygon aggregation bins.</p>


```csharp
public CIMBinningVisualization()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBinningVisualization.</p>


```csharp
public CIMBinningVisualization Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Reconstructs the CIMBinningVisualization with a specified state from a JSON encoding.</p>


```csharp
public static CIMBinningVisualization FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandardDeviationMultiplier

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Gets or sets the standard deviation multiplier used to define the data min, max values for visualization.</p>


```csharp
public StandardDeviationMultiplier StandardDeviationMultiplier { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBinningVisualization and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBinningVisualization.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


