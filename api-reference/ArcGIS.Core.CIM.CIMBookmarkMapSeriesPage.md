# CIMBookmarkMapSeriesPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">A map series page based on a bookmark.</p>


## Object Signature

```csharp
public class CIMBookmarkMapSeriesPage : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBookmarkMapSeriesPage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">A map series page based on a bookmark.</p>


```csharp
public CIMBookmarkMapSeriesPage()
```
### BookmarkName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Gets or sets the bookmark.</p>


```csharp
public string BookmarkName { get; set; }
```
### Category

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Gets or sets the category. Category lets you organize your pages into groups.</p>


```csharp
public string Category { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBookmarkMapSeriesPage.</p>


```csharp
public CIMBookmarkMapSeriesPage Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Reconstructs the CIMBookmarkMapSeriesPage with a specified state from a JSON encoding.</p>


```csharp
public static CIMBookmarkMapSeriesPage FromJson(string json, JsonDeserializationSettings settings = null)
```
### MapURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Gets or sets the map.</p>


```csharp
public string MapURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBookmarkMapSeriesPage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeriesPage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


