# CIMGridZoneLabelPosition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Represents the state of a label at a given position on a MapGrid.</p>


## Object Signature

```csharp
public class CIMGridZoneLabelPosition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGridZoneLabelPosition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Represents the state of a label at a given position on a MapGrid.</p>


```csharp
public CIMGridZoneLabelPosition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGridZoneLabelPosition.</p>


```csharp
public CIMGridZoneLabelPosition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Reconstructs the CIMGridZoneLabelPosition with a specified state from a JSON encoding.</p>


```csharp
public static CIMGridZoneLabelPosition FromJson(string json, JsonDeserializationSettings settings = null)
```
### OffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Gets or sets the offset in the X-Coordinate direction between the label and grid components.</p>


```csharp
public double OffsetX { get; set; }
```
### OffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Gets or sets the offset in the Y-Coordinate direction between the label and grid components.</p>


```csharp
public double OffsetY { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGridZoneLabelPosition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the label at this position is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridZoneLabelPosition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


