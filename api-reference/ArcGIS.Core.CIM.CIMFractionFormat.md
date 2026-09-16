# CIMFractionFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Represents a fraction format.</p>


## Object Signature

```csharp
public class CIMFractionFormat : CIMNumberFormat, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFractionFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Represents a fraction format.</p>


```csharp
public CIMFractionFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFractionFormat.</p>


```csharp
public CIMFractionFormat Clone()
```
### Factor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Gets or sets the maximum number of digits for the numerator or denominator, or the denominator of the formatted fraction.</p>


```csharp
public int Factor { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMFractionFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMFractionFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### Option

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Gets or sets the fraction option determines how the numerator and denominator of the fraction are treated.</p>


```csharp
public FractionOption Option { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFractionFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFractionFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


