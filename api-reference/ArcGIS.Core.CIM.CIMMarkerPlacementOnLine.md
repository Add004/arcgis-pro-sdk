# CIMMarkerPlacementOnLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Represents a marker placement on the line.</p>


## Object Signature

```csharp
public class CIMMarkerPlacementOnLine : CIMMarkerStrokePlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacementOnLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Represents a marker placement on the line.</p>


```csharp
public CIMMarkerPlacementOnLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerPlacementOnLine.</p>


```csharp
public CIMMarkerPlacementOnLine Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerPlacementOnLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerPlacementOnLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelativeTo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Gets or sets the location on a line where a marker will be placed. The direction of the line is determined by the direction in which the line was digitized.</p>


```csharp
public PlacementOnLineRelativeTo RelativeTo { get; set; }
```
### StartPointOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Gets or sets the distances from a specified location on a line that a marker will be placed.</p>


```csharp
public double StartPointOffset { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerPlacementOnLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacementOnLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


