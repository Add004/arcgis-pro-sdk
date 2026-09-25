# CIMLadderGridLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Represents internal labels for a MapGrid.</p>


## Object Signature

```csharp
public class CIMLadderGridLine : CIMGridLine, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLadderGridLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Represents internal labels for a MapGrid.</p>


```csharp
public CIMLadderGridLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLadderGridLine.</p>


```csharp
public CIMLadderGridLine Clone()
```
### DynamicStringTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Gets or sets the dynamic string used to represent the ladder label of the map grid.</p>


```csharp
public string DynamicStringTemplate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Reconstructs the CIMLadderGridLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMLadderGridLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### GapX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Gets or sets the gap in the X-Coordinate direction between the label extent and grid components.</p>


```csharp
public double GapX { get; set; }
```
### GapY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Gets or sets the gap in the Y-Coordinate direction between the label extent and grid components.</p>


```csharp
public double GapY { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Gets or sets the position of the ladder labels.</p>


```csharp
public GridLadderLabelPosition Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLadderGridLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLadderGridLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


