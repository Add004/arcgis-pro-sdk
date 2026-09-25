# CIMBookmarkDocument

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Represents a bookmark document which is the document type used for saving .bkmx files.</p>


## Object Signature

```csharp
public class CIMBookmarkDocument : CIMVersion, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBookmarkDocument()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Represents a bookmark document which is the document type used for saving .bkmx files.</p>


```csharp
public CIMBookmarkDocument()
```
### Bookmarks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Gets or sets the bookmarks.</p>


```csharp
public CIMBookmark[] Bookmarks { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBookmarkDocument.</p>


```csharp
public CIMBookmarkDocument Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Reconstructs the CIMBookmarkDocument with a specified state from a JSON encoding.</p>


```csharp
public static CIMBookmarkDocument FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Gets or sets the spatial reference.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBookmarkDocument and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkDocument.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


