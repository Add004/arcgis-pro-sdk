# CIMMultipatchFeatureTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Represents a multipatch feature template.</p>


## Object Signature

```csharp
public class CIMMultipatchFeatureTemplate : CIMBasicRowTemplate, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultipatchFeatureTemplate()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Represents a multipatch feature template.</p>


```csharp
public CIMMultipatchFeatureTemplate()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMultipatchFeatureTemplate.</p>


```csharp
public CIMMultipatchFeatureTemplate Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Reconstructs the CIMMultipatchFeatureTemplate with a specified state from a JSON encoding.</p>


```csharp
public static CIMMultipatchFeatureTemplate FromJson(string json, JsonDeserializationSettings settings = null)
```
### GalleryMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is gallery mode.</p>


```csharp
public bool GalleryMode { get; set; }
```
### Models

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Gets or sets the models.</p>


```csharp
public CIMMultipatchFeatureTemplateModel[] Models { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMultipatchFeatureTemplate and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipatchFeatureTemplate.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


