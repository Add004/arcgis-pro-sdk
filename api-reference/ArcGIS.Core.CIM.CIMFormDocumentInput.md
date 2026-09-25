# CIMFormDocumentInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts documents.</p>


## Object Signature

```csharp
public class CIMFormDocumentInput : CIMFormAttachmentInput, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFormDocumentInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Represents an attachment input that accepts documents.</p>


```csharp
public CIMFormDocumentInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFormDocumentInput.</p>


```csharp
public CIMFormDocumentInput Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Reconstructs the CIMFormDocumentInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMFormDocumentInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxFileSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Gets or sets the maximum size of an attachment for this element in bytes. If set (or defaulted)
to -1, there is no maximum file size.</p>


```csharp
public long MaxFileSize { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFormDocumentInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFormDocumentInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


