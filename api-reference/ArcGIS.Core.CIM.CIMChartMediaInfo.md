# CIMChartMediaInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Represents chart media info.</p>


## Object Signature

```csharp
public abstract class CIMChartMediaInfo : CIMMediaInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartMediaInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Represents chart media info.</p>


```csharp
protected CIMChartMediaInfo()
```
### AltText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the alt text.</p>


```csharp
public string AltText { get; set; }
```
### Caption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the caption.</p>


```csharp
public string Caption { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the color ramp to be used for charts.</p>


```csharp
public CIMFixedColorRamp ColorRamp { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the fields.</p>


```csharp
public string[] Fields { get; set; }
```
### MaximumAxisValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the maximum axis value.</p>


```csharp
public double MaximumAxisValue { get; set; }
```
### NormalizeField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizeField { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartMediaInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


