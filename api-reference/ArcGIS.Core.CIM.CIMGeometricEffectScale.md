# CIMGeometricEffectScale

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Represents the rotate geometric effect which creates a dynamic line or polygon scaled by a specified factor. Vertices are moved in relation to the center point of a feature envelope. Values greater than 1 move vertices away from the center point. Values between 0 and 1 move vertices toward the center point. Values less than 0 draw an inverse dynamic line or polygon where the vertices have crossed to the other side of the center point.</p>


## Object Signature

```csharp
public class CIMGeometricEffectScale : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectScale()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Represents the rotate geometric effect which creates a dynamic line or polygon scaled by a specified factor. Vertices are moved in relation to the center point of a feature envelope. Values greater than 1 move vertices away from the center point. Values between 0 and 1 move vertices toward the center point. Values less than 0 draw an inverse dynamic line or polygon where the vertices have crossed to the other side of the center point.</p>


```csharp
public CIMGeometricEffectScale()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectScale.</p>


```csharp
public CIMGeometricEffectScale Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectScale with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectScale FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectScale and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Gets or sets the amount of change in size of a symbol in the x-axis. The value is expressed in terms of a ratio/percentage.</p>


```csharp
public double XScaleFactor { get; set; }
```
### YScaleFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectScale.yml" sourcestartlinenumber="1">Gets or sets the amount of change in size of a symbol in the y-axis. The value is expressed in terms of a ratio/percentage.</p>


```csharp
public double YScaleFactor { get; set; }
```


