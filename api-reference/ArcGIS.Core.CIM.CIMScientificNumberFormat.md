# CIMScientificNumberFormat

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Represents scientific number format.</p>


## Object Signature

```csharp
public class CIMScientificNumberFormat : CIMNumberFormat, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMScientificNumberFormat()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Represents scientific number format.</p>


```csharp
public CIMScientificNumberFormat()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Creates a deep copy of CIMScientificNumberFormat.</p>


```csharp
public CIMScientificNumberFormat Clone()
```
### DecimalPlaces

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Gets or sets the number of decimal places to show.</p>


```csharp
public int DecimalPlaces { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Reconstructs the CIMScientificNumberFormat with a specified state from a JSON encoding.</p>


```csharp
public static CIMScientificNumberFormat FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMScientificNumberFormat and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMScientificNumberFormat.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


