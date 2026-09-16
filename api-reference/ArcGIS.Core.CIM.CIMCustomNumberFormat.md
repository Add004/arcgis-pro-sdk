# CIMCustomNumberFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Represents a custom number format.</p>


## Object Signature

```csharp
public class CIMCustomNumberFormat : CIMNumberFormat, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCustomNumberFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Represents a custom number format.</p>


```csharp
public CIMCustomNumberFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCustomNumberFormat.</p>


```csharp
public CIMCustomNumberFormat Clone()
```
### FormatString

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Gets or sets the format string (e.g. ###-##-####).</p>


```csharp
public string FormatString { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMCustomNumberFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMCustomNumberFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCustomNumberFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCustomNumberFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


