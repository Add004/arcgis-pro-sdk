# CIMGeometricEffectControlMeasureLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Represents the control measure line geometric effect.</p>


## Object Signature

```csharp
public class CIMGeometricEffectControlMeasureLine : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectControlMeasureLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Represents the control measure line geometric effect.</p>


```csharp
public CIMGeometricEffectControlMeasureLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectControlMeasureLine.</p>


```csharp
public CIMGeometricEffectControlMeasureLine Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectControlMeasureLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectControlMeasureLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Rule

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Gets or sets the style of effect.</p>


```csharp
public GeometricEffectControlMeasureLineRule Rule { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectControlMeasureLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Gets or sets a width value.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectControlMeasureLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


