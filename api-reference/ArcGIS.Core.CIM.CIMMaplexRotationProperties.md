# CIMMaplexRotationProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Represents Maplex rotation properties.</p>


## Object Signature

```csharp
public class CIMMaplexRotationProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexRotationProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Represents Maplex rotation properties.</p>


```csharp
public CIMMaplexRotationProperties()
```
### AdditionalAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets additional angle to add to the data value.</p>


```csharp
public int AdditionalAngle { get; set; }
```
### AlignLabelToAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to align the label to the angle.</p>


```csharp
public bool AlignLabelToAngle { get; set; }
```
### AlignmentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets the alignment type.</p>


```csharp
public MaplexRotationAlignmentType AlignmentType { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexRotationProperties.</p>


```csharp
public CIMMaplexRotationProperties Clone()
```
### Enable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to enable rotation.</p>


```csharp
public bool Enable { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexRotationProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexRotationProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### PerpendicularToAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to place the label perpendicular to the angle.</p>


```csharp
public bool PerpendicularToAngle { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotationExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns rotation as a number.
When both RotationField and RotationExpressionInfo are present RotationExpressionInfo is used.</p>


```csharp
public CIMExpressionInfo RotationExpressionInfo { get; set; }
```
### RotationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets the rotation field to get values from.</p>


```csharp
public string RotationField { get; set; }
```
### RotationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Gets or sets the rotation type.</p>


```csharp
public MaplexLabelRotationType RotationType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexRotationProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexRotationProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


