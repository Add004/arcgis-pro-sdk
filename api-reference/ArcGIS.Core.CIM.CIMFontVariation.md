# CIMFontVariation

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Represents a font variation tag name and value. This is sometimes referred to as a variation-axis tag and variation-axis value.</p>


## Object Signature

```csharp
public class CIMFontVariation : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFontVariation()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Represents a font variation tag name and value. This is sometimes referred to as a variation-axis tag and variation-axis value.</p>


```csharp
public CIMFontVariation()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFontVariation.</p>


```csharp
public CIMFontVariation Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Reconstructs the CIMFontVariation with a specified state from a JSON encoding.</p>


```csharp
public static CIMFontVariation FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TagName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Gets or sets the font variation tag name. This is a four letter identifier for a particular axis of variation, specified in the font.</p>


```csharp
public string TagName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFontVariation and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Gets or sets the numeric value representing a particular font variation value.</p>


```csharp
public double Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFontVariation.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


