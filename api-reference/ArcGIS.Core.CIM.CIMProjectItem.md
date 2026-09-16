# CIMProjectItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Represents an item in the project.</p>


## Object Signature

```csharp
public class CIMProjectItem : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProjectItem()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Represents an item in the project.</p>


```csharp
public CIMProjectItem()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets an identifier for this item that the user provides and can be displayed instead of the Name.</p>


```csharp
public string Alias { get; set; }
```
### CatalogPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets the catalog path of the project item.</p>


```csharp
public string CatalogPath { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProjectItem.</p>


```csharp
public CIMProjectItem Clone()
```
### ConsolidatePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to consolidate the path of the project item.</p>


```csharp
public bool ConsolidatePath { get; set; }
```
### ConsolidationResources

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets consolidation resources string array of the project item.</p>


```csharp
public string[] ConsolidationResources { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Reconstructs the CIMProjectItem with a specified state from a JSON encoding.</p>


```csharp
public static CIMProjectItem FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets the system assigned unique identifier of the project item.</p>


```csharp
public string ID { get; set; }
```
### ItemType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets the item type of the project item.</p>


```csharp
public string ItemType { get; set; }
```
### MetadataURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the metadata.</p>


```csharp
public string MetadataURI { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets the name of the project item.</p>


```csharp
public string Name { get; set; }
```
### PathHint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets the path hint of the project item.</p>


```csharp
public string PathHint { get; set; }
```
### PathSaveRelative

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the item is saved with relative paths.</p>


```csharp
public bool PathSaveRelative { get; set; }
```
### PropertiesXML

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets properties of the item as XML.</p>


```csharp
public string PropertiesXML { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceModifiedTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets modified time of the item as a time instant.</p>


```csharp
public TimeInstant SourceModifiedTime { get; set; }
```
### SourceURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Gets or sets the source URI of the item. Set if sourced from an external item such as an item on a portal.</p>


```csharp
public string SourceURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProjectItem and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectItem.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


