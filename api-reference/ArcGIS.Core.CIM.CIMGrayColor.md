# CIMGrayColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Represents a grayscale color defined by lightness.</p>


## Object Signature

```csharp
public class CIMGrayColor : CIMColor, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">A color in a grayscale model, where the value of lightness is defined.</p>


## Members

### CIMGrayColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Represents a grayscale color defined by lightness.</p>


```csharp
public CIMGrayColor()
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array.</p>


```csharp
protected override short AlphaIndex()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGrayColor.</p>


```csharp
public CIMGrayColor Clone()
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Creates a gray color with default values.</p>


```csharp
protected override void CreateDefaultValues()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Reconstructs the CIMGrayColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMGrayColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### Level

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Gets and sets the gray level.</p>


```csharp
public float Level { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGrayColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGrayColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


