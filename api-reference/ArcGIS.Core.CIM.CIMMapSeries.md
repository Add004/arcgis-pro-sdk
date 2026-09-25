# CIMMapSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">The Map series object represents a means to create multi-page PDF or
based off of fields in the index layer.</p>


## Object Signature

```csharp
public abstract class CIMMapSeries : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">The Map series object represents a means to create multi-page PDF or
based off of fields in the index layer.</p>


```csharp
protected CIMMapSeries()
```
### CurrentPageID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">Gets or sets the current page Id.</p>


```csharp
public long CurrentPageID { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the map series is enabled on the layout.</p>


```csharp
public bool Enabled { get; set; }
```
### MapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">Gets or sets the URI of the MapFrame to which MapSeries is linked.</p>


```csharp
public string MapFrameName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StartingPageNumber

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">Gets or sets the starting page number.</p>


```csharp
public int StartingPageNumber { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


