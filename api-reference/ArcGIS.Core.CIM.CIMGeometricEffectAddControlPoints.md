# CIMGeometricEffectAddControlPoints

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Represents the add control points geometric effect.</p>


## Object Signature

```csharp
public class CIMGeometricEffectAddControlPoints : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Dynamically adds geometry control points to a feature to dictate the placement of markers or other effect properties that leverage control points. Control points are placed at angles or deflection based on the AngleTolerance value.</p>


## Members

### CIMGeometricEffectAddControlPoints()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Represents the add control points geometric effect.</p>


```csharp
public CIMGeometricEffectAddControlPoints()
```
### AngleTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Gets or sets the value below which a control point will be placed.</p>


```csharp
public double AngleTolerance { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectAddControlPoints.</p>


```csharp
public CIMGeometricEffectAddControlPoints Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectAddControlPoints with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectAddControlPoints FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectAddControlPoints and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectAddControlPoints.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


