# CIMCMYKColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Represents a color in the CMYK color model.</p>


## Object Signature

```csharp
public class CIMCMYKColor : CIMColor, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">A color in the CMYK (cyan, magenta, yellow, black) color model. CMYK is a subtractive color model commonly used in color printing.</p>


## Members

### CIMCMYKColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Represents a color in the CMYK color model.</p>


```csharp
public CIMCMYKColor()
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array.</p>


```csharp
protected override short AlphaIndex()
```
### C

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Gets and sets cyan.</p>


```csharp
public float C { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCMYKColor.</p>


```csharp
public CIMCMYKColor Clone()
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Creates a CMYK color with default values.</p>


```csharp
protected override void CreateDefaultValues()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Reconstructs the CIMCMYKColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMCMYKColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### K

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Gets and sets black.</p>


```csharp
public float K { get; set; }
```
### M

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Gets and sets magenta.</p>


```csharp
public float M { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCMYKColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCMYKColor.yml" sourcestartlinenumber="1">Gets and sets yellow.</p>


```csharp
public float Y { get; set; }
```


