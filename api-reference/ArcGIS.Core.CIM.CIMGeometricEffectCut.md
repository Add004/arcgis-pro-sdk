# CIMGeometricEffectCut

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Represents the cut geometric effect which creates a dynamic line that is shorter on one or both ends than the line feature or polygon outline.</p>


## Object Signature

```csharp
public class CIMGeometricEffectCut : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectCut()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Represents the cut geometric effect which creates a dynamic line that is shorter on one or both ends than the line feature or polygon outline.</p>


```csharp
public CIMGeometricEffectCut()
```
### BeginCut

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Gets or sets the distance from the beginning of a line that the display of the stroke starts. The beginning of the line is determined by the direction in which the line was digitized.</p>


```csharp
public double BeginCut { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectCut.</p>


```csharp
public CIMGeometricEffectCut Clone()
```
### EndCut

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Gets or sets the distance from the end of a line that the display of the stroke ends. The end of the line is determined by the direction in which the line was digitized.</p>


```csharp
public double EndCut { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectCut with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectCut FromJson(string json, JsonDeserializationSettings settings = null)
```
### Invert

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the effect should be applied in the opposite manner. This displays the stroke symbol only at the ends of the line and leaves the rest of the line unsymbolized.</p>


```csharp
public bool Invert { get; set; }
```
### MiddleCut

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Gets or sets the distance around the middle of a line that the display of the stroke is interrupted.</p>


```csharp
public double MiddleCut { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectCut and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectCut.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


