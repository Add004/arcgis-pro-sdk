# CIMXYZColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Represents a color in the XYZ color model.</p>


## Object Signature

```csharp
public class CIMXYZColor : CIMColor, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">A color in the XYZ color space which is based on direct measurements of the human eye.</p>


## Members

### CIMXYZColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Represents a color in the XYZ color model.</p>


```csharp
public CIMXYZColor()
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array.</p>


```csharp
protected override short AlphaIndex()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMXYZColor.</p>


```csharp
public CIMXYZColor Clone()
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Creates an XYZ color with default values.</p>


```csharp
protected override void CreateDefaultValues()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Reconstructs the CIMXYZColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMXYZColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMXYZColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Gets and sets X.</p>


```csharp
public float X { get; set; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Gets and sets Y.</p>


```csharp
public float Y { get; set; }
```
### Z

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYZColor.yml" sourcestartlinenumber="1">Gets and sets Z.</p>


```csharp
public float Z { get; set; }
```


