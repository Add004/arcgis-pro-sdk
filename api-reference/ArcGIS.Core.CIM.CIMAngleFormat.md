# CIMAngleFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Represents an angle format.</p>


## Object Signature

```csharp
public class CIMAngleFormat : CIMNumericFormatBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAngleFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Represents an angle format.</p>


```csharp
public CIMAngleFormat()
```
### AngleInDegrees

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display the angle in degrees.</p>


```csharp
public bool AngleInDegrees { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAngleFormat.</p>


```csharp
public CIMAngleFormat Clone()
```
### DisplayDegrees

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display degrees.</p>


```csharp
public bool DisplayDegrees { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMAngleFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMAngleFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAngleFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAngleFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


