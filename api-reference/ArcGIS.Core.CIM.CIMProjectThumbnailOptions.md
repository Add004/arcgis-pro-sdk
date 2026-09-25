# CIMProjectThumbnailOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">A collection of options governing project thumbnail generation.</p>


## Object Signature

```csharp
public class CIMProjectThumbnailOptions : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProjectThumbnailOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">A collection of options governing project thumbnail generation.</p>


```csharp
public CIMProjectThumbnailOptions()
```
### AutomaticGenerationSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating how an automatically generated thumbnail is created.</p>


```csharp
public ProjectThumbnailAutomaticGenerationSource AutomaticGenerationSource { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProjectThumbnailOptions.</p>


```csharp
public CIMProjectThumbnailOptions Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Reconstructs the CIMProjectThumbnailOptions with a specified state from a JSON encoding.</p>


```csharp
public static CIMProjectThumbnailOptions FromJson(string json, JsonDeserializationSettings settings = null)
```
### GenerationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating how a thumbnail should be generated for a project.</p>


```csharp
public ProjectThumbnailGenerationMethod GenerationMethod { get; set; }
```
### MapURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating the path of a map to be used in the automatic generation of a project thumbnail.</p>


```csharp
public string MapURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProjectThumbnailOptions and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProjectThumbnailOptions.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


