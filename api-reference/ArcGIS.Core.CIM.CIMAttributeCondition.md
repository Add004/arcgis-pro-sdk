# CIMAttributeCondition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Represents an attribute condition.</p>


## Object Signature

```csharp
public class CIMAttributeCondition : CIMCondition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAttributeCondition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Represents an attribute condition.</p>


```csharp
public CIMAttributeCondition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAttributeCondition.</p>


```csharp
public CIMAttributeCondition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Reconstructs the CIMAttributeCondition with a specified state from a JSON encoding.</p>


```csharp
public static CIMAttributeCondition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAttributeCondition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Gets or sets the where clause.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttributeCondition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


