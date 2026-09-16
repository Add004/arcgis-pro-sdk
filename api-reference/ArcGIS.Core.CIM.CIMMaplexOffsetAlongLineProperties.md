# CIMMaplexOffsetAlongLineProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Represents Maplex offset along the line properties.</p>


## Object Signature

```csharp
public class CIMMaplexOffsetAlongLineProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaplexOffsetAlongLineProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Represents Maplex offset along the line properties.</p>


```csharp
public CIMMaplexOffsetAlongLineProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaplexOffsetAlongLineProperties.</p>


```csharp
public CIMMaplexOffsetAlongLineProperties Clone()
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Gets or sets the distance along the line.</p>


```csharp
public double Distance { get; set; }
```
### DistanceUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Gets or sets the distance unit.</p>


```csharp
public MaplexUnit DistanceUnit { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMaplexOffsetAlongLineProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaplexOffsetAlongLineProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelAnchorPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Gets or sets the label anchor point for positioning along the line.</p>


```csharp
public MaplexLabelAnchorPoint LabelAnchorPoint { get; set; }
```
### PlacementMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Gets or sets the placement method.</p>


```csharp
public MaplexOffsetAlongLineMethod PlacementMethod { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaplexOffsetAlongLineProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Tolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Gets or sets the tolerance.</p>


```csharp
public double Tolerance { get; set; }
```
### UseLineDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the line direction.</p>


```csharp
public bool UseLineDirection { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaplexOffsetAlongLineProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


