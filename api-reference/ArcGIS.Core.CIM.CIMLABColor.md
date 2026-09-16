# CIMLABColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Represents a color defined in the LAB color space.</p>


## Object Signature

```csharp
public class CIMLABColor : CIMColor, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Defines colors in the CIELAB color space, which is a color-opponent space with dimension L for lightness and a and b for the color-opponent dimensions.</p>


## Members

### CIMLABColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Represents a color defined in the LAB color space.</p>


```csharp
public CIMLABColor()
```
### A

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Gets and sets a*.</p>


```csharp
public float A { get; set; }
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array.</p>


```csharp
protected override short AlphaIndex()
```
### B

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Gets and sets b*.</p>


```csharp
public float B { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLABColor.</p>


```csharp
public CIMLABColor Clone()
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Creates a LAB color with default values.</p>


```csharp
protected override void CreateDefaultValues()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Reconstructs the CIMLABColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMLABColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### L

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Gets and sets L*.</p>


```csharp
public float L { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLABColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLABColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


