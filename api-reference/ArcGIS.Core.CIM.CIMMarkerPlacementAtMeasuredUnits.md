# CIMMarkerPlacementAtMeasuredUnits

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Represents marker placement at geometry M values.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementAtMeasuredUnits : CIMMarkerStrokePlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementAtMeasuredUnits()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Represents marker placement at geometry M values.</p>


```csharp
public CIMMarkerPlacementAtMeasuredUnits()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementAtMeasuredUnits.</p>


```csharp
public CIMMarkerPlacementAtMeasuredUnits Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementAtMeasuredUnits with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementAtMeasuredUnits FromJson(string json, JsonDeserializationSettings settings = null)
```
### Interval

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Gets or sets the interval of measured units used to place markers.</p>


```csharp
public double Interval { get; set; }
```
### PlaceAtExtremities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether markers should be placed at extremities.</p>


```csharp
public bool PlaceAtExtremities { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SkipMarkerRate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Gets or sets the rate of markers to skip.</p>


```csharp
public int SkipMarkerRate { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementAtMeasuredUnits and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtMeasuredUnits.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


