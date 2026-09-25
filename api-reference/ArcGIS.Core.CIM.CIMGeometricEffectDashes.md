# CIMGeometricEffectDashes

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Represents the dashes geometric effect which creates a dynamic multipart line geometry from a line feature or the outline of a polygon based on a template.</p>


## Object Signature

```csharp
public class CIMGeometricEffectDashes : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectDashes()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Represents the dashes geometric effect which creates a dynamic multipart line geometry from a line feature or the outline of a polygon based on a template.</p>


```csharp
public CIMGeometricEffectDashes()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectDashes.</p>


```csharp
public CIMGeometricEffectDashes Clone()
```
### ControlPointEnding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Gets or sets the line dash ending position.</p>


```csharp
public LineDashEnding ControlPointEnding { get; set; }
```
### CustomEndingOffset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Gets or sets where the pattern should end relative to the ending point of the geometry. Negative numbers indicate a shift to the left and positive numbers a shift to the right. This property is only applied if the LineDashEnding is set to Custom.</p>


```csharp
public double CustomEndingOffset { get; set; }
```
### DashTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Gets or sets the distance for each dash and gap. There can be multiple dash and gap values to form a complex pattern.</p>


```csharp
public double[] DashTemplate { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectDashes with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectDashes FromJson(string json, JsonDeserializationSettings settings = null)
```
### LineDashEnding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Gets or sets the setting which determines how the strokes with dash patterns and other patterns (pictures, placement effects) are handled at the end points of the line geometry's segments.</p>


```csharp
public LineDashEnding LineDashEnding { get; set; }
```
### OffsetAlongLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Gets or sets the position where the pattern should begin relative to the starting point of the geometry. It shifts the entire pattern along the line the specified distance. Negative values indicate a shift to the left and positive numbers a shift to the right. This property is only applied if LineDashEnding is set to NoConstraint or Custom.</p>


```csharp
public double OffsetAlongLine { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectDashes and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectDashes.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


