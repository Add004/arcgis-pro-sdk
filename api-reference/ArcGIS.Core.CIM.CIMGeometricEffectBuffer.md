# CIMGeometricEffectBuffer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Represents the buffer geometric effect which creates a dynamic polygon with a specified distance around features.</p>


## Object Signature

```csharp
public class CIMGeometricEffectBuffer : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectBuffer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Represents the buffer geometric effect which creates a dynamic polygon with a specified distance around features.</p>


```csharp
public CIMGeometricEffectBuffer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectBuffer.</p>


```csharp
public CIMGeometricEffectBuffer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectBuffer with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectBuffer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Gets or sets the distance from the feature. This distance is either from the edge of the marker, the edge of the stroke or the edge of the polygon outline.</p>


```csharp
public double Size { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectBuffer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectBuffer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


