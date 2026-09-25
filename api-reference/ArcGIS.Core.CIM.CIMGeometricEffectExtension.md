# CIMGeometricEffectExtension

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Represents the extension geometric effect which creates a dynamic line that is extended from either the beginning or the end of the line feature at a specified deflection angle and length.</p>


## Object Signature

```csharp
public class CIMGeometricEffectExtension : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectExtension()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Represents the extension geometric effect which creates a dynamic line that is extended from either the beginning or the end of the line feature at a specified deflection angle and length.</p>


```csharp
public CIMGeometricEffectExtension()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectExtension.</p>


```csharp
public CIMGeometricEffectExtension Clone()
```
### Deflection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Gets or sets the deflection angle used for the extension. A value of 0 indicates no deflection.</p>


```csharp
public double Deflection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectExtension with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectExtension FromJson(string json, JsonDeserializationSettings settings = null)
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Gets or sets the length of the extension that is dynamically created.</p>


```csharp
public double Length { get; set; }
```
### Origin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Gets or sets the origin of the extension to add to the line. The beginning and end of the line is defined by the direction the line was digitized.</p>


```csharp
public GeometricEffectExtensionOrigin Origin { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectExtension and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectExtension.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


