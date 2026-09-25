# CIMMarkerPlacementAtExtremities

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Represents marker placement at extremities which places markers at only one or both endpoints of a line.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementAtExtremities : CIMMarkerStrokePlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementAtExtremities()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Represents marker placement at extremities which places markers at only one or both endpoints of a line.</p>


```csharp
public CIMMarkerPlacementAtExtremities()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementAtExtremities.</p>


```csharp
public CIMMarkerPlacementAtExtremities Clone()
```
### ExtremityPlacement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Gets or sets which ends of the line a marker will be placed.</p>


```csharp
public ExtremityPlacement ExtremityPlacement { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementAtExtremities with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementAtExtremities FromJson(string json, JsonDeserializationSettings settings = null)
```
### OffsetAlongLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Gets or sets the distance from the ends of a line that the marker will be placed.</p>


```csharp
public double OffsetAlongLine { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementAtExtremities and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAtExtremities.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


