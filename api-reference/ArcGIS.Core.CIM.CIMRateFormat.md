# CIMRateFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Represents a rate format.</p>


## Object Signature

```csharp
public class CIMRateFormat : CIMNumericFormatBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRateFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Represents a rate format.</p>


```csharp
public CIMRateFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRateFormat.</p>


```csharp
public CIMRateFormat Clone()
```
### Factor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Gets or sets the rate factor.</p>


```csharp
public double Factor { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMRateFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMRateFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Gets or sets the label appended to the formatted rate number.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRateFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRateFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


