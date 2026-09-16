# CIMExteriorTick

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Class that represents an exterior tick for a grid.</p>


## Object Signature

```csharp
public class CIMExteriorTick : CIMTick, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMExteriorTick()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Class that represents an exterior tick for a grid.</p>


```csharp
public CIMExteriorTick()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Creates a deep copy of CIMExteriorTick.</p>


```csharp
public CIMExteriorTick Clone()
```
### DrawPerpendicular

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to the draw the ticks perpendicular to the map grid edges.</p>


```csharp
public bool DrawPerpendicular { get; set; }
```
### EdgeAffinity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Gets or sets the collection of edges the ticks or the labels draw on.
If the collection is empty, the drawing is made on the entire area of interest.</p>


```csharp
public int[] EdgeAffinity { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Reconstructs the CIMExteriorTick with a specified state from a JSON encoding.</p>


```csharp
public static CIMExteriorTick FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMExteriorTick and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMExteriorTick.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


