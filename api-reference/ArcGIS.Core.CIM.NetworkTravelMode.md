# NetworkTravelMode

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Represents a network travel mode. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
[DataContract]
public sealed class NetworkTravelMode
```


## Members

### NetworkTravelMode()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Represents a network travel mode. This class is reserved for esri internal use only.</p>


```csharp
public NetworkTravelMode()
```
### AttributeParameterValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the attribute parameter values.</p>


```csharp
[DataMember(Name = "attributeParameterValues", Order = 7, IsRequired = false, EmitDefaultValue = true)]
public NetworkTravelModeParameterValue[] AttributeParameterValues { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the description.</p>


```csharp
[DataMember(Name = "description", Order = 2, IsRequired = false, EmitDefaultValue = true)]
public string Description { get; set; }
```
### DistanceAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the distance attribute name.</p>


```csharp
[DataMember(Name = "distanceAttributeName", Order = 5, IsRequired = false, EmitDefaultValue = true)]
public string DistanceAttributeName { get; set; }
```
### FromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Reconstructs the NetworkTravelMode with a specified state from a JSON encoding.</p>


```csharp
public static NetworkTravelMode FromJson(string json)
```
### ImpedanceAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the impedance attribute name.</p>


```csharp
[DataMember(Name = "impedanceAttributeName", Order = 3, IsRequired = false, EmitDefaultValue = true)]
public string ImpedanceAttributeName { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the name.</p>


```csharp
[DataMember(Name = "name", Order = 0, IsRequired = false, EmitDefaultValue = true)]
public string Name { get; set; }
```
### OutputGeometryPrecision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the output geometry precision.</p>


```csharp
[DataMember(Name = "simplificationTolerance", Order = 10, IsRequired = false, EmitDefaultValue = true)]
public double? OutputGeometryPrecision { get; set; }
```
### OutputGeometryPrecisionUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the output geometry precision units.</p>


```csharp
public esriUnits OutputGeometryPrecisionUnits { get; set; }
```
### OutputGeometryPrecisionUnitsString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the output geometry precision units as a string.</p>


```csharp
[DataMember(Name = "simplificationToleranceUnits", Order = 11, IsRequired = false, EmitDefaultValue = true)]
public string OutputGeometryPrecisionUnitsString { get; set; }
```
### RestrictUTurns

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets a setting which indicates how U-Turns should be restricted in the analysis.</p>


```csharp
public esriNetworkForwardStarBacktrack RestrictUTurns { get; set; }
```
### RestrictUTurnsString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets a setting which indicates how U-Turns should be restricted in the analysis as a string.</p>


```csharp
[DataMember(Name = "uturnAtJunctions", Order = 9, IsRequired = false, EmitDefaultValue = true)]
public string RestrictUTurnsString { get; set; }
```
### RestrictionAttributeNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the restriction attribute name.</p>


```csharp
[DataMember(Name = "restrictionAttributeNames", Order = 6, IsRequired = false, EmitDefaultValue = true)]
public string[] RestrictionAttributeNames { get; set; }
```
### TimeAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the time attribute name.</p>


```csharp
[DataMember(Name = "timeAttributeName", Order = 4, IsRequired = false, EmitDefaultValue = true)]
public string TimeAttributeName { get; set; }
```
### ToJson()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NetworkTravelMode and its current state.</p>


```csharp
public string ToJson()
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">JSON encoding of the NetworkTravelMode and its current state.</p>


```csharp
public override string ToString()
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets the type.</p>


```csharp
[DataMember(Name = "type", Order = 1, IsRequired = false, EmitDefaultValue = true)]
public string Type { get; set; }
```
### UseHierarchy

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NetworkTravelMode.yml" sourcestartlinenumber="1">Gets and sets a boolean indicating whether or not to use the hierarchy.</p>


```csharp
[DataMember(Name = "useHierarchy", Order = 8, IsRequired = false, EmitDefaultValue = true)]
public bool UseHierarchy { get; set; }
```


