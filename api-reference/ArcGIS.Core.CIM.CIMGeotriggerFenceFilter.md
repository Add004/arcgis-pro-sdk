# CIMGeotriggerFenceFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Represents a geotrigger fence filter.</p>


## Object Signature

```csharp
public class CIMGeotriggerFenceFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeotriggerFenceFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Represents a geotrigger fence filter.</p>


```csharp
public CIMGeotriggerFenceFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeotriggerFenceFilter.</p>


```csharp
public CIMGeotriggerFenceFilter Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMGeotriggerFenceFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeotriggerFenceFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometryURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Gets or sets the geometry.</p>


```csharp
public string GeometryURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeotriggerFenceFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Gets or sets the where clause.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerFenceFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


