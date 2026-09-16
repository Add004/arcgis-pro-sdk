# CIMSubtypeGroupTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Represents a subtype group table that works with tables enabled with subtypes.</p>


## Object Signature

```csharp
public class CIMSubtypeGroupTable : CIMStandaloneTable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSubtypeGroupTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Represents a subtype group table that works with tables enabled with subtypes.</p>


```csharp
public CIMSubtypeGroupTable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSubtypeGroupTable.</p>


```csharp
public CIMSubtypeGroupTable Clone()
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this group table is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Reconstructs the CIMSubtypeGroupTable with a specified state from a JSON encoding.</p>


```csharp
public static CIMSubtypeGroupTable FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandaloneTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Gets or sets the standalone tables as an array of table repository paths.</p>


```csharp
public string[] StandaloneTables { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSubtypeGroupTable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubtypeGroupTable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


