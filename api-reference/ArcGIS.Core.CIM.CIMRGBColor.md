# CIMRGBColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Represents a color in the RGB color model.</p>


## Object Signature

```csharp
public class CIMRGBColor : CIMColor, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">A color in the RGB (red, green, blue) color model. RGB is an additive, or light-emissive model based on red, green, and blue values.</p>


## Members

### CIMRGBColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Represents a color in the RGB color model.</p>


```csharp
public CIMRGBColor()
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array.</p>


```csharp
protected override short AlphaIndex()
```
### B

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Gets and sets blue.</p>


```csharp
public float B { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRGBColor.</p>


```csharp
public CIMRGBColor Clone()
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Creates an RGB color with default values.</p>


```csharp
protected override void CreateDefaultValues()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Reconstructs the CIMRGBColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMRGBColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### G

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Gets an sets green.</p>


```csharp
public float G { get; set; }
```
### R

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Gets and sets red.</p>


```csharp
public float R { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRGBColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRGBColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


