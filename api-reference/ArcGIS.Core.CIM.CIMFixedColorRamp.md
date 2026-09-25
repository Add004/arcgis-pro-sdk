# CIMFixedColorRamp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Represents a color scheme composed of discrete colors.</p>


## Object Signature

```csharp
public class CIMFixedColorRamp : CIMColorRamp, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">A color scheme composed of an ordered list of discrete colors.</p>


## Members

### CIMFixedColorRamp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Represents a color scheme composed of discrete colors.</p>


```csharp
public CIMFixedColorRamp()
```
### Arrangement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Gets or sets the arrangement type.</p>


```csharp
public FixedColorRampArrangementType Arrangement { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFixedColorRamp.</p>


```csharp
public CIMFixedColorRamp Clone()
```
### Colors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Gets or sets the ordered list of colors in the color scheme.</p>


```csharp
public CIMColor[] Colors { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Reconstructs the CIMFixedColorRamp with a specified state from a JSON encoding.</p>


```csharp
public static CIMFixedColorRamp FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFixedColorRamp and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFixedColorRamp.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


