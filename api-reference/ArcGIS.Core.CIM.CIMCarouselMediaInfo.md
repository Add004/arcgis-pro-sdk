# CIMCarouselMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Represents carousel media info.</p>


## Object Signature

```csharp
public class CIMCarouselMediaInfo : CIMMediaInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMCarouselMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Represents carousel media info.</p>


```csharp
public CIMCarouselMediaInfo()
```
### AltText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the alt text.</p>


```csharp
public string AltText { get; set; }
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public string Caption { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMCarouselMediaInfo.</p>


```csharp
public CIMCarouselMediaInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMCarouselMediaInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMCarouselMediaInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### MediaInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the array of media infos.</p>


```csharp
public CIMMediaInfo[] MediaInfos { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMCarouselMediaInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMCarouselMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


