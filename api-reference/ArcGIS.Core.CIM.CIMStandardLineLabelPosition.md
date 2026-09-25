# CIMStandardLineLabelPosition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Represents standard label engine line label position.</p>


## Object Signature

```csharp
public class CIMStandardLineLabelPosition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStandardLineLabelPosition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Represents standard label engine line label position.</p>


```csharp
public CIMStandardLineLabelPosition()
```
### Above

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement above lines.</p>


```csharp
public bool Above { get; set; }
```
### AtEnd

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement at the end of lines.</p>


```csharp
public bool AtEnd { get; set; }
```
### AtStart

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement at the start of lines.</p>


```csharp
public bool AtStart { get; set; }
```
### Below

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement below lines.</p>


```csharp
public bool Below { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStandardLineLabelPosition.</p>


```csharp
public CIMStandardLineLabelPosition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Reconstructs the CIMStandardLineLabelPosition with a specified state from a JSON encoding.</p>


```csharp
public static CIMStandardLineLabelPosition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Horizontal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement horizontally.</p>


```csharp
public bool Horizontal { get; set; }
```
### InLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow along lines at the best position.</p>


```csharp
public bool InLine { get; set; }
```
### Left

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement to the left of the line.</p>


```csharp
public bool Left { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets the offset from the line.</p>


```csharp
public double Offset { get; set; }
```
### OnTop

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement on top of lines.</p>


```csharp
public bool OnTop { get; set; }
```
### Parallel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement parallel to lines.</p>


```csharp
public bool Parallel { get; set; }
```
### Perpendicular

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement perpendicular to lines.</p>


```csharp
public bool Perpendicular { get; set; }
```
### ProduceCurvedLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to produce curved labels.</p>


```csharp
public bool ProduceCurvedLabels { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Right

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to allow placement to the right of the line.</p>


```csharp
public bool Right { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStandardLineLabelPosition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardLineLabelPosition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


