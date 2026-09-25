# CIMAttachmentsMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Represents attachment media info.</p>


## Object Signature

```csharp
public class CIMAttachmentsMediaInfo : CIMMediaInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAttachmentsMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Represents attachment media info.</p>


```csharp
public CIMAttachmentsMediaInfo()
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public string Caption { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAttachmentsMediaInfo.</p>


```csharp
public CIMAttachmentsMediaInfo Clone()
```
### ContentType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the content MIME type. Example: (image/png, image/jpeg, audio/mp3).</p>


```csharp
public string ContentType { get; set; }
```
### DisplayType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the display type.</p>


```csharp
public AttachmentDisplayType DisplayType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMAttachmentsMediaInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMAttachmentsMediaInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SortField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the attachment sort field.</p>


```csharp
public string SortField { get; set; }
```
### SortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the attachment sort order.</p>


```csharp
public SortOrderType SortOrder { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAttachmentsMediaInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAttachmentsMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


