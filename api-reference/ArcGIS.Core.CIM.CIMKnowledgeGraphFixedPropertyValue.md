# CIMKnowledgeGraphFixedPropertyValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Represents a fixed string property value.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphFixedPropertyValue : CIMKnowledgeGraphPropertyValue, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphFixedPropertyValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Represents a fixed string property value.</p>


```csharp
public CIMKnowledgeGraphFixedPropertyValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphFixedPropertyValue.</p>


```csharp
public CIMKnowledgeGraphFixedPropertyValue Clone()
```
### FixedValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Gets or sets the fixed value of this property value.</p>


```csharp
public string FixedValue { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphFixedPropertyValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphFixedPropertyValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphFixedPropertyValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphFixedPropertyValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


