# CIMServiceSubTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Represents a service subtable.</p>


## Object Signature

```csharp
public class CIMServiceSubTable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMServiceSubTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Represents a service subtable.</p>


```csharp
public CIMServiceSubTable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMServiceSubTable.</p>


```csharp
public CIMServiceSubTable Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Reconstructs the CIMServiceSubTable with a specified state from a JSON encoding.</p>


```csharp
public static CIMServiceSubTable FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SelectionSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Gets or sets the URI of the selection set for the service subtable.</p>


```csharp
public string SelectionSetURI { get; set; }
```
### SubTableID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Gets or sets the sub table ID.</p>


```csharp
public string SubTableID { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMServiceSubTable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceSubTable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


