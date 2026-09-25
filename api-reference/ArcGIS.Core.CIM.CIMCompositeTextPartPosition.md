# CIMCompositeTextPartPosition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Represents the text part position properties on a callout part.</p>


## Object Signature

```csharp
public class CIMCompositeTextPartPosition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCompositeTextPartPosition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Represents the text part position properties on a callout part.</p>


```csharp
public CIMCompositeTextPartPosition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCompositeTextPartPosition.</p>


```csharp
public CIMCompositeTextPartPosition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Reconstructs the CIMCompositeTextPartPosition with a specified state from a JSON encoding.</p>


```csharp
public static CIMCompositeTextPartPosition FromJson(string json, JsonDeserializationSettings settings = null)
```
### HorizontalAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Gets or sets the horizontal alignment of the text part.</p>


```csharp
public HorizontalAlignment HorizontalAlignment { get; set; }
```
### IsPartWithinCalloutBox

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the text part will be contained within the main callout.
If this is set to true, the main callout will expand to encompass this text part,
and a line will be draw separating the part from the rest of the callout.
This line will have the same symbol as the callout outline and will only draw if
the text part is above or below the top and bottom margins of the middle text.</p>


```csharp
public bool IsPartWithinCalloutBox { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SplitOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Gets or sets the split offset of the text part. This determines how much of a gap
there is between the callout border and any part of the text part intersecting the border
If this is set to wider than the callout width, none of the associated callout line will draw.</p>


```csharp
public double SplitOffset { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCompositeTextPartPosition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Gets or sets the vertical alignment of the text part.</p>


```csharp
public VerticalAlignment VerticalAlignment { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Gets or sets the X offset of the text part.</p>


```csharp
public double XOffset { get; set; }
```
### YOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCompositeTextPartPosition.yml" sourcestartlinenumber="1">Gets or sets the Y offset of the text part.</p>


```csharp
public double YOffset { get; set; }
```


