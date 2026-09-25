# CIMSpotColor

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Represents a spot color.</p>


## Object Signature

```csharp
public class CIMSpotColor : CIMColor, INotifyPropertyChanged, IXmlSerializable, IEquatable<CIMColor>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">A color defined by a specific ink standard and typically used in offset printing where the color corresponds to a pure or premixed ink. When a spot color is displayed on the screen the alternative color is used.</p>


## Members

### CIMSpotColor()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Represents a spot color.</p>


```csharp
public CIMSpotColor()
```
### AlphaIndex()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Returns the index of the alpha color in the color array.</p>


```csharp
protected override short AlphaIndex()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSpotColor.</p>


```csharp
public CIMSpotColor Clone()
```
### CreateDefaultValues()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Creates a Spot color with default values.</p>


```csharp
protected override void CreateDefaultValues()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Reconstructs the CIMSpotColor with a specified state from a JSON encoding.</p>


```csharp
public static CIMSpotColor FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Gets or sets the spot color name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Tint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Gets and sets tint.</p>


```csharp
public float Tint { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSpotColor and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSpotColor.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


