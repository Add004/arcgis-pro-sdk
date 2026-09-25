# CIMInteriorTick

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Class that represents an interior tick for a grid.</p>


## Object Signature

```csharp
public class CIMInteriorTick : CIMTick, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMInteriorTick()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Class that represents an interior tick for a grid.</p>


```csharp
public CIMInteriorTick()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Creates a deep copy of CIMInteriorTick.</p>


```csharp
public CIMInteriorTick Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Reconstructs the CIMInteriorTick with a specified state from a JSON encoding.</p>


```csharp
public static CIMInteriorTick FromJson(string json, JsonDeserializationSettings settings = null)
```
### IndicateDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the ticks show the direction away from the origin.
If false, the ticks bisect the center of the grid line.</p>


```csharp
public bool IndicateDirection { get; set; }
```
### Pattern

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Gets or sets the pattern for the interior ticks.</p>


```csharp
public CIMGridPattern Pattern { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMInteriorTick and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInteriorTick.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


