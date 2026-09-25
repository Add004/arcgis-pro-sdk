# CIMMaterializedViewProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Properties relevant to query layers based on materialized views.</p>


## Object Signature

```csharp
public class CIMMaterializedViewProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMaterializedViewProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Properties relevant to query layers based on materialized views.</p>


```csharp
public CIMMaterializedViewProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMaterializedViewProperties.</p>


```csharp
public CIMMaterializedViewProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMaterializedViewProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMaterializedViewProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaterializedViewExpiration

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Gets or sets the number of days after creating a materialized view that it is set to expire.</p>


```csharp
public int MaterializedViewExpiration { get; set; }
```
### MaterializedViewQuery

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Gets or sets the original definition of the materialized view.</p>


```csharp
public string MaterializedViewQuery { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMaterializedViewProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMaterializedViewProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


