# CIMBookmarkMapSeries

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Bookmark map series is a means to create a series of map pages based on saved bookmarks.</p>


## Object Signature

```csharp
public class CIMBookmarkMapSeries : CIMMapSeries, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBookmarkMapSeries()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Bookmark map series is a means to create a series of map pages based on saved bookmarks.</p>


```csharp
public CIMBookmarkMapSeries()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBookmarkMapSeries.</p>


```csharp
public CIMBookmarkMapSeries Clone()
```
### ExtentOptions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Gets or sets the extent fitting options.</p>


```csharp
public ExtentFitType ExtentOptions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Reconstructs the CIMBookmarkMapSeries with a specified state from a JSON encoding.</p>


```csharp
public static CIMBookmarkMapSeries FromJson(string json, JsonDeserializationSettings settings = null)
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Gets or sets the value of the margin.</p>


```csharp
public double Margin { get; set; }
```
### MarginType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Gets or sets the type of margin.</p>


```csharp
public UnitType MarginType { get; set; }
```
### MarginUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Gets or sets the units of the margin.</p>


```csharp
public LinearUnit MarginUnits { get; set; }
```
### Pages

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Gets or sets the pages.</p>


```csharp
public CIMBookmarkMapSeriesPage[] Pages { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleRounding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Gets or sets the specified value to which the scale rounds.</p>


```csharp
public double ScaleRounding { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBookmarkMapSeries and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBookmarkMapSeries.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


