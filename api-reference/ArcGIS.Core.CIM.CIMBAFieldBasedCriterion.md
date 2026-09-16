# CIMBAFieldBasedCriterion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis field-based criterion.</p>


## Object Signature

```csharp
public class CIMBAFieldBasedCriterion : CIMBASuitabilityAnalysisCriterion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAFieldBasedCriterion()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis field-based criterion.</p>


```csharp
public CIMBAFieldBasedCriterion()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAFieldBasedCriterion.</p>


```csharp
public CIMBAFieldBasedCriterion Clone()
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Gets or sets the Selected Field Name.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Reconstructs the CIMBAFieldBasedCriterion with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAFieldBasedCriterion FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAFieldBasedCriterion and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAFieldBasedCriterion.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


