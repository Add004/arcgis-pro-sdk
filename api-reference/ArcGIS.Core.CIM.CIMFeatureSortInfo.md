# CIMFeatureSortInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Contains information about the field name and sort order used to draw features.</p>


## Object Signature

```csharp
public class CIMFeatureSortInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFeatureSortInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Contains information about the field name and sort order used to draw features.</p>


```csharp
public CIMFeatureSortInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFeatureSortInfo.</p>


```csharp
public CIMFeatureSortInfo Clone()
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Gets or sets the name of the Field.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMFeatureSortInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMFeatureSortInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SortDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating the sort direction.</p>


```csharp
public SortOrderType SortDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFeatureSortInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureSortInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


