# CIMPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Represents the page information associated with a layout.</p>


## Object Signature

```csharp
public class CIMPage : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Represents the page information associated with a layout.</p>


```csharp
public CIMPage()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPage.</p>


```csharp
public CIMPage Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Reconstructs the CIMPage with a specified state from a JSON encoding.</p>


```csharp
public static CIMPage FromJson(string json, JsonDeserializationSettings settings = null)
```
### Guides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets the guides on a layout.</p>


```csharp
public CIMGuide[] Guides { get; set; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets the height of the layout in page units.</p>


```csharp
public double Height { get; set; }
```
### Margin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets the margin for the page.</p>


```csharp
public CIMMargin Margin { get; set; }
```
### PrinterPreferences

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets the printer preferences for the page.</p>


```csharp
public CIMPrinterPreferences PrinterPreferences { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowGuides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether guides should be displayed on the layout.</p>


```csharp
public bool ShowGuides { get; set; }
```
### ShowMargin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the printer margin should be displayed on the layout.</p>


```csharp
public bool ShowMargin { get; set; }
```
### ShowRulers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether rulers should be displayed on the layout.</p>


```csharp
public bool ShowRulers { get; set; }
```
### SmallestRulerDivision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets the smallest ruler division.</p>


```csharp
public double SmallestRulerDivision { get; set; }
```
### StretchElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether elements should be stretched when the page size is changed.</p>


```csharp
public bool StretchElements { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Units

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets the page units for the layout.</p>


```csharp
public LinearUnit Units { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Gets or sets the width of the layout in page units.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


