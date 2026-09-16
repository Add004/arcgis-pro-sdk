# CIMNetworkDatasetLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Represents a network dataset layer.</p>


## Object Signature

```csharp
public class CIMNetworkDatasetLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkDatasetLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Represents a network dataset layer.</p>


```csharp
public CIMNetworkDatasetLayer()
```
### ClassifyRestrictionsByPreferenceLevel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to classify restrictions by preference level.</p>


```csharp
public bool ClassifyRestrictionsByPreferenceLevel { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkDatasetLayer.</p>


```csharp
public CIMNetworkDatasetLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets data connection to the network dataset.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DirtyAreaRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the dirty area renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer DirtyAreaRenderer { get; set; }
```
### DisplayNetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the display network attribute.</p>


```csharp
public string DisplayNetworkAttribute { get; set; }
```
### EdgeRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the edge renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer EdgeRenderer { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkDatasetLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkDatasetLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### JunctionRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the junction renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer JunctionRenderer { get; set; }
```
### MissingElementRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the missing element renderer.</p>


```csharp
public CIMNetworkDatasetElementCompositeRenderer MissingElementRenderer { get; set; }
```
### NetworkSourceDisplayFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the network source display filters.</p>


```csharp
public CIMNetworkSourceDisplayFilter[] NetworkSourceDisplayFilters { get; set; }
```
### OneWayRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the one-way renderer.</p>


```csharp
public CIMNetworkDatasetElementCompositeRenderer OneWayRenderer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RestrictionNetworkAttributes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the restriction network attributes.</p>


```csharp
public string[] RestrictionNetworkAttributes { get; set; }
```
### RestrictionRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the restriction renderer.</p>


```csharp
public CIMNetworkDatasetElementCompositeRenderer RestrictionRenderer { get; set; }
```
### RestrictionStatusRenderers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the restriction status renderers.</p>


```csharp
public CIMRestrictionStatusRenderer[] RestrictionStatusRenderers { get; set; }
```
### SystemJunctionRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the system junction renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer SystemJunctionRenderer { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkDatasetLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TrafficNetworkAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the traffic network attribute.</p>


```csharp
public string TrafficNetworkAttribute { get; set; }
```
### TrafficRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the traffic renderer.</p>


```csharp
public CIMNetworkDatasetTrafficRenderer TrafficRenderer { get; set; }
```
### TravelModeContext

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the travel mode context.</p>


```csharp
public CIMNetworkTravelModeDefinitionContext TravelModeContext { get; set; }
```
### TraversableRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the traversable renderer.</p>


```csharp
public CIMNetworkDatasetElementCompositeRenderer TraversableRenderer { get; set; }
```
### TurnRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the turn renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer TurnRenderer { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


