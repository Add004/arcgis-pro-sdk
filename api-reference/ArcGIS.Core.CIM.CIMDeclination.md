# CIMDeclination

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Represents the properties of a declination calculated using World Magnetic Model.</p>


## Object Signature

```csharp
public class CIMDeclination : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDeclination()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Represents the properties of a declination calculated using World Magnetic Model.</p>


```csharp
public CIMDeclination()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDeclination.</p>


```csharp
public CIMDeclination Clone()
```
### Degrees

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Gets or sets the degrees of declination.</p>


```csharp
public int Degrees { get; set; }
```
### Direction

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Gets or sets the direction the declination is reckoned from.</p>


```csharp
public DeclinationDirection Direction { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Reconstructs the CIMDeclination with a specified state from a JSON encoding.</p>


```csharp
public static CIMDeclination FromJson(string json, JsonDeserializationSettings settings = null)
```
### Mils

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Gets or sets the mil radians of declination.</p>


```csharp
public double Mils { get; set; }
```
### Minutes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Gets or sets the minutes of declination.</p>


```csharp
public int Minutes { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Seconds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Gets or sets the seconds of declination.</p>


```csharp
public int Seconds { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDeclination and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDeclination.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


