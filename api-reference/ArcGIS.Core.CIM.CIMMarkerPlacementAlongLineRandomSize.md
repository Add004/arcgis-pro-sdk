# CIMMarkerPlacementAlongLineRandomSize

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Represents marker placement along the line which places randomly sized markers evenly along a line or polygon outline.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementAlongLineRandomSize : CIMMarkerPlacementAlongLine, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementAlongLineRandomSize()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Represents marker placement along the line which places randomly sized markers evenly along a line or polygon outline.</p>


```csharp
public CIMMarkerPlacementAlongLineRandomSize()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementAlongLineRandomSize.</p>


```csharp
public CIMMarkerPlacementAlongLineRandomSize Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementAlongLineRandomSize with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementAlongLineRandomSize FromJson(string json, JsonDeserializationSettings settings = null)
```
### Randomization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Gets or sets the amount of randomness to be used for the size and rotation of the markers on the line. The size and rotation of the marker will vary for individual markers.</p>


```csharp
public PlacementRandomlyAlongLineRandomization Randomization { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Seed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Gets or sets the starting value for generating a random number. This random number is used by the Randomization property to determine the marker shape.</p>


```csharp
public int Seed { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementAlongLineRandomSize and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementAlongLineRandomSize.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


