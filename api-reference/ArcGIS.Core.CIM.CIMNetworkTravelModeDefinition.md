# CIMNetworkTravelModeDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">The network travel mode is used to configure a group of cost, traversability, and other analysis configurations.</p>


## Object Signature

```csharp
public class CIMNetworkTravelModeDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkTravelModeDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">The network travel mode is used to configure a group of cost, traversability, and other analysis configurations.</p>


```csharp
public CIMNetworkTravelModeDefinition()
```
### AttributeParameterValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the array of network attribute parameter definition values.</p>


```csharp
public CIMNetworkAttributeParameterDefinitionValue[] AttributeParameterValues { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkTravelModeDefinition.</p>


```csharp
public CIMNetworkTravelModeDefinition Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### DistanceAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the distance attribute name.</p>


```csharp
public string DistanceAttributeName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkTravelModeDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkTravelModeDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ImpedanceAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the impedance attribute name.</p>


```csharp
public string ImpedanceAttributeName { get; set; }
```
### ModeType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the mode type.</p>


```csharp
public string ModeType { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### OutputGeometryPrecisionUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the output geometry precision units.</p>


```csharp
public LinearUnit OutputGeometryPrecisionUnits { get; set; }
```
### OutputGeometryPrecisionValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the output geometry precision value.</p>


```csharp
public double OutputGeometryPrecisionValue { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RestrictionAttributeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the array of restriction attribute names.</p>


```csharp
public string[] RestrictionAttributeNames { get; set; }
```
### TimeAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the time attribute name.</p>


```csharp
public string TimeAttributeName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkTravelModeDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UTurnAtJunctionsPolicy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets the u-turn at junctions policy for traversal between stops.</p>


```csharp
public esriNetworkForwardStarBacktrack UTurnAtJunctionsPolicy { get; set; }
```
### UseHierarchy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use hierarchy.</p>


```csharp
public bool UseHierarchy { get; set; }
```
### UseOutputGeometryPrecision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use output geometry precision.</p>


```csharp
public bool UseOutputGeometryPrecision { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


