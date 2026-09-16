# CIMMGRSGridLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Represents a gridLine to draw the 100,000 MGRS grids.</p>


## Object Signature

```csharp
public class CIMMGRSGridLine : CIMGridLine, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMGRSGridLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Represents a gridLine to draw the 100,000 MGRS grids.</p>


```csharp
public CIMMGRSGridLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMGRSGridLine.</p>


```csharp
public CIMMGRSGridLine Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Reconstructs the CIMMGRSGridLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMMGRSGridLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelPosition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Gets or sets the position of the label in the 100,000m grid square.</p>


```csharp
public MGRSLabelPosition LabelPosition { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMGRSGridLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Gets or sets the offset in the x-coordinate direction for the grid label.</p>


```csharp
public double XOffset { get; set; }
```
### YOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMGRSGridLine.yml" sourcestartlinenumber="1">Gets or sets the offset in the y-coordinate direction for the grid label.</p>


```csharp
public double YOffset { get; set; }
```


