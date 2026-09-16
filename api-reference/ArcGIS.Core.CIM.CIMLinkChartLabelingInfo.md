# CIMLinkChartLabelingInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Represents the link chart labeling information.</p>


## Object Signature

```csharp
public abstract class CIMLinkChartLabelingInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartLabelingInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Represents the link chart labeling information.</p>


```csharp
protected CIMLinkChartLabelingInfo()
```
### LabelBackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets Link label background color.</p>


```csharp
public CIMColor LabelBackgroundColor { get; set; }
```
### LabelFontColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets Link Label font color.</p>


```csharp
public CIMColor LabelFontColor { get; set; }
```
### LabelFontFamilyName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets the link label font family name of the font. e.g. Comic Sans.</p>


```csharp
public string LabelFontFamilyName { get; set; }
```
### LabelFontSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets Link label font size.</p>


```csharp
public double LabelFontSize { get; set; }
```
### LabelFontStyleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets the style name for the link label font family. e.g. Regular, Bold, or Italic.</p>


```csharp
public string LabelFontStyleName { get; set; }
```
### LabelFontType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets Link label font type.</p>


```csharp
public FontType LabelFontType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the labels are shown.</p>


```csharp
public bool ShowLabels { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartLabelingInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


