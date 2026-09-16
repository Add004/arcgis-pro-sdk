# CIMFieldDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Represents a field description.</p>


## Object Signature

```csharp
public class CIMFieldDescription : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFieldDescription()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Represents a field description.</p>


```csharp
public CIMFieldDescription()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets the field alias.</p>


```csharp
public string Alias { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFieldDescription.</p>


```csharp
public CIMFieldDescription Clone()
```
### FieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets the field name.</p>


```csharp
public string FieldName { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Reconstructs the CIMFieldDescription with a specified state from a JSON encoding.</p>


```csharp
public static CIMFieldDescription FromJson(string json, JsonDeserializationSettings settings = null)
```
### Highlight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the field is highlighted.</p>


```csharp
public bool Highlight { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the field is read only.</p>


```csharp
public bool ReadOnly { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SearchMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets search mode to use when searching for values in this field.</p>


```csharp
public DataSearchMode SearchMode { get; set; }
```
### Searchable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the values from this field should be included in the search.</p>


```csharp
public bool Searchable { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFieldDescription and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueAsRatio

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the field value is a ratio (used only by geoprocessing).</p>


```csharp
public bool ValueAsRatio { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the field is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFieldDescription.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


