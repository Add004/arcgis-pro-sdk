# CIMImageMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Represents image media info.</p>


## Object Signature

```csharp
public class CIMImageMediaInfo : CIMMediaInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMImageMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Represents image media info.</p>


```csharp
public CIMImageMediaInfo()
```
### AltText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the alt text.</p>


```csharp
public string AltText { get; set; }
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public string Caption { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMImageMediaInfo.</p>


```csharp
public CIMImageMediaInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMImageMediaInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMImageMediaInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### LinkURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the link URL.</p>


```csharp
public string LinkURL { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceURL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the source URL.</p>


```csharp
public string SourceURL { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMImageMediaInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMImageMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


