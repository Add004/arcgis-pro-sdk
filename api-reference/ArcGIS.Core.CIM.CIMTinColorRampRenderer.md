# CIMTinColorRampRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Represents a TIN color ramp renderer.</p>


## Object Signature

```csharp
public abstract class CIMTinColorRampRenderer : CIMTerrainAttributeRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinColorRampRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Represents a TIN color ramp renderer.</p>


```csharp
protected CIMTinColorRampRenderer()
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the class breaks.</p>


```csharp
public CIMClassBreak[] Breaks { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### CursorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the cursor type.</p>


```csharp
public TerrainDrawCursorType CursorType { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the minimum break.</p>


```csharp
public double MinimumBreak { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowClassGaps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show class gaps.</p>


```csharp
public bool ShowClassGaps { get; set; }
```
### SortClassesAscending

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether classes are ascending.</p>


```csharp
public bool SortClassesAscending { get; set; }
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Gets or sets the base symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinColorRampRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


