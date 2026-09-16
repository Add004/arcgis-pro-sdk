# CIMKnowledgeGraphExpressionPropertyValue

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Represents a property value from an expression.</p>


## Object Signature

```csharp
public class CIMKnowledgeGraphExpressionPropertyValue : CIMKnowledgeGraphPropertyValue, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKnowledgeGraphExpressionPropertyValue()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Represents a property value from an expression.</p>


```csharp
public CIMKnowledgeGraphExpressionPropertyValue()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKnowledgeGraphExpressionPropertyValue.</p>


```csharp
public CIMKnowledgeGraphExpressionPropertyValue Clone()
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Gets or sets the expression info of this property value.</p>


```csharp
public CIMExpressionInfo Expression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Reconstructs the CIMKnowledgeGraphExpressionPropertyValue with a specified state from a JSON encoding.</p>


```csharp
public static CIMKnowledgeGraphExpressionPropertyValue FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKnowledgeGraphExpressionPropertyValue and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKnowledgeGraphExpressionPropertyValue.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


