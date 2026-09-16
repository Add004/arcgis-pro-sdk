# CIMDocumentInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Represents high level information for a document.</p>


## Object Signature

```csharp
public class CIMDocumentInfo : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDocumentInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Represents high level information for a document.</p>


```csharp
public CIMDocumentInfo()
```
### ActiveMapRepositoryPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the path of the active map.</p>


```csharp
public string ActiveMapRepositoryPath { get; set; }
```
### Antialiasing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the anti-aliasing properties. Currently overridden by application settings.</p>


```csharp
public esriBGLAntialiasingMode Antialiasing { get; set; }
```
### Author

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the author of the document.</p>


```csharp
public string Author { get; set; }
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the category of the document.</p>


```csharp
public string Category { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDocumentInfo.</p>


```csharp
public CIMDocumentInfo Clone()
```
### Comments

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the comments of the document.</p>


```csharp
public string Comments { get; set; }
```
### Credits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the credits of the document.</p>


```csharp
public string Credits { get; set; }
```
### DocumentTitle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the title of the document.</p>


```csharp
public string DocumentTitle { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMDocumentInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMDocumentInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### HyperlinkBase

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the hyperlink base path of the document.</p>


```csharp
public string HyperlinkBase { get; set; }
```
### Keywords

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the keywords of the document.</p>


```csharp
public string Keywords { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SavePreview

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to save a preview image.</p>


```csharp
public bool SavePreview { get; set; }
```
### Subject

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the subject of the document.</p>


```csharp
public string Subject { get; set; }
```
### TextAntialiasing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets the text anti-aliasing properties. Currently overridden by application settings.</p>


```csharp
public esriBGLTextAAlias TextAntialiasing { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDocumentInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseRelativePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to save with relative paths. In typical Pro usage (e.g. saving projects or .lyrx files) this is set to true.</p>


```csharp
public bool UseRelativePath { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDocumentInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


