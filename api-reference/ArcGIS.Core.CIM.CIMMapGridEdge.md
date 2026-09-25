# CIMMapGridEdge

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Represents a map grid edge.</p>


## Object Signature

```csharp
public class CIMMapGridEdge : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapGridEdge()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Represents a map grid edge.</p>


```csharp
public CIMMapGridEdge()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapGridEdge.</p>


```csharp
public CIMMapGridEdge Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Reconstructs the CIMMapGridEdge with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapGridEdge FromJson(string json, JsonDeserializationSettings settings = null)
```
### PartIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Gets or sets the part index of the map grid edge.</p>


```csharp
public int PartIndex { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SegmentIndices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Gets or sets the segment indices of the segments making up the edge.</p>


```csharp
public int[] SegmentIndices { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapGridEdge and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGridEdge.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


