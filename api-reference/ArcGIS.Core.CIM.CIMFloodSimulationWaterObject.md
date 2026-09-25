# CIMFloodSimulationWaterObject

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterObject.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation object.</p>


## Object Signature

```csharp
public abstract class CIMFloodSimulationWaterObject : CIMFloodSimulationObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationWaterObject()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterObject.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation object.</p>


```csharp
protected CIMFloodSimulationWaterObject()
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterObject.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WaterFlowRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterObject.yml" sourcestartlinenumber="1">Gets or sets an array of water flow rates (in cubic meters/second) over durations (in seconds).</p>


```csharp
public CIMRateDuration[] WaterFlowRate { get; set; }
```
### WaterRateDisplayUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterObject.yml" sourcestartlinenumber="1">Gets or sets the water rate display unit.</p>


```csharp
public LinearUnit WaterRateDisplayUnit { get; set; }
```
### WaterRateTransitionTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterObject.yml" sourcestartlinenumber="1">Gets or sets the time (in seconds) to transition between water rates.</p>


```csharp
public double WaterRateTransitionTime { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationWaterObject.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


