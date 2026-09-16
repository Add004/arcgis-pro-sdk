# CIMHSLColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Represents a color defined by hue, saturation, and lightness.</p>


## Object Signature

```csharp
public class CIMHSLColor : CIMColor, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Transforms RGB values by defining the hue, saturation, and lightness of the color. The three values do not represent individual color channels but the HSL coordinates used to define the color in the RGB color model.</p>


## Members

### CIMHSLColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Represents a color defined by hue, saturation, and lightness.</p>


```csharp
public CIMHSLColor()
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array.</p>


```csharp
protected override short AlphaIndex()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMHSLColor.</p>


```csharp
public CIMHSLColor Clone()
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Creates an HSL color with default values.</p>


```csharp
protected override void CreateDefaultValues()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Reconstructs the CIMHSLColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMHSLColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### H

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Gets and sets hue.</p>


```csharp
public float H { get; set; }
```
### L

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Gets and sets lightness.</p>


```csharp
public float L { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### S

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Gets and sets saturation.</p>


```csharp
public float S { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMHSLColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMHSLColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


