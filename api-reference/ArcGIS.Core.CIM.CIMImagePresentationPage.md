# CIMImagePresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Represents an image media presentation page.</p>


## Object Signature

```csharp
public class CIMImagePresentationPage : CIMPresentationPage, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMImagePresentationPage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Represents an image media presentation page.</p>


```csharp
public CIMImagePresentationPage()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMImagePresentationPage.</p>


```csharp
public CIMImagePresentationPage Clone()
```
### FitType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Gets or sets the image content fit type.</p>


```csharp
public PresentationMediaContentFitType FitType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Reconstructs the CIMImagePresentationPage with a specified state from a JSON encoding.</p>


```csharp
public static CIMImagePresentationPage FromJson(string json, JsonDeserializationSettings settings = null)
```
### ImageURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the image.</p>


```csharp
public string ImageURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Gets or sets the source URL of the image. Typically the source of the image copied into the ImageURI.</p>


```csharp
public string SourceURL { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMImagePresentationPage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImagePresentationPage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


