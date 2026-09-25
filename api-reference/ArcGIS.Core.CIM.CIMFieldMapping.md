# CIMFieldMapping

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Represents a field mapping that maps fields from source layer or table to target layer or table.</p>


## Object Signature

```csharp
public class CIMFieldMapping : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFieldMapping()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Represents a field mapping that maps fields from source layer or table to target layer or table.</p>


```csharp
public CIMFieldMapping()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFieldMapping.</p>


```csharp
public CIMFieldMapping Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Reconstructs the CIMFieldMapping with a specified state from a JSON encoding.</p>


```csharp
public static CIMFieldMapping FromJson(string json, JsonDeserializationSettings settings = null)
```
### MappingExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Gets or sets the expression for mapping from source layer or table to target layer or table.</p>


```csharp
public CIMExpressionInfo MappingExpressionInfo { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Gets or sets the URI of the source layer or table.</p>


```csharp
public string SourceURI { get; set; }
```
### TargetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Gets or sets the URI of the target layer or table.</p>


```csharp
public string TargetURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFieldMapping and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldMapping.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


