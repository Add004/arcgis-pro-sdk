# CIMMultipatchFeatureTemplateModel

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Represents a multipatch feature template model.</p>


## Object Signature

```csharp
public class CIMMultipatchFeatureTemplateModel : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultipatchFeatureTemplateModel()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Represents a multipatch feature template model.</p>


```csharp
public CIMMultipatchFeatureTemplateModel()
```
### Camera

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Gets or sets the camera.</p>


```csharp
public CIMViewCamera Camera { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMultipatchFeatureTemplateModel.</p>


```csharp
public CIMMultipatchFeatureTemplateModel Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Reconstructs the CIMMultipatchFeatureTemplateModel with a specified state from a JSON encoding.</p>


```csharp
public static CIMMultipatchFeatureTemplateModel FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsActive

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is active.</p>


```csharp
public bool IsActive { get; set; }
```
### ModelSourceURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Gets or sets the file path to the original model source.</p>


```csharp
public string ModelSourceURI { get; set; }
```
### ModelURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the model.</p>


```csharp
public string ModelURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ThumbnailURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the thumbnail.</p>


```csharp
public string ThumbnailURI { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMultipatchFeatureTemplateModel and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplateModel.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


