# CIMKnowledgeLinkChartOrganicLayoutSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Contains settings to be used in organic layout calculations.</p>


## Object Signature

```csharp
public class CIMKnowledgeLinkChartOrganicLayoutSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeLinkChartOrganicLayoutSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Contains settings to be used in organic layout calculations.</p>


```csharp
public CIMKnowledgeLinkChartOrganicLayoutSettings()
```
### AbsoluteIdealEdgeLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the value, in degrees, to use for the ideal edge length during
layout calculations when the IdealEdgeLengthType is 'absoluteValue'.
Only used for geographic layouts.</p>


```csharp
public double AbsoluteIdealEdgeLength { get; set; }
```
### AutoComputeRepulsionRadius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the repulsion radius is automatically computed or if
it is computed according to 'RepulsionRadiusMultiplier'.</p>


```csharp
public bool AutoComputeRepulsionRadius { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeLinkChartOrganicLayoutSettings.</p>


```csharp
public CIMKnowledgeLinkChartOrganicLayoutSettings Clone()
```
### ComputationTimeBudget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the computation time budget, in seconds.
The maximum count of iterations of the force directed algorithm is computed
based on the size of the link chart and this computation budget, assuming computations
are executed by a theoretical CPU with some known characteristics.
Higher values lead to better looking layouts.</p>


```csharp
public double ComputationTimeBudget { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeLinkChartOrganicLayoutSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeLinkChartOrganicLayoutSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### IdealEdgeLengthType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the ideal edge length type which determines which property to use to compute the ideal edge length.
Only used for geographic layouts.
When the value is 'AbsoluteValue', the 'AbsoluteIdealEdgeLength' property is used.
When the value is 'Multiplier', the 'MultiplicativeIdealEdgeLength' property is used.</p>


```csharp
public LinkChartLayoutIdealEdgeLengthType IdealEdgeLengthType { get; set; }
```
### MultiplicativeIdealEdgeLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the value used to multiply the default edge length to determine
the ideal edge length during layout calculations, when the
IdealEdgeLengthType is 'multiplier'.
Only used for geographic layouts.</p>


```csharp
public double MultiplicativeIdealEdgeLength { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RepulsionRadiusMultiplier

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Gets or sets the value to be used for the repulsion radius multiplier.
The repulsion radius is computed as the repulsion radius multiplier multiplied by the actual ideal edge length.
Only used when 'AutoComputeRepulsionRadius' is false.</p>


```csharp
public double RepulsionRadiusMultiplier { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeLinkChartOrganicLayoutSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeLinkChartOrganicLayoutSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


