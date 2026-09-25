# CIMTinUniqueValueRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a TIN unique value renderer.</p>


## Object Signature

```csharp
public abstract class CIMTinUniqueValueRenderer : CIMTerrainAttributeRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinUniqueValueRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a TIN unique value renderer.</p>


```csharp
protected CIMTinUniqueValueRenderer()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ColorScheme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp name.</p>


```csharp
public string ColorScheme { get; set; }
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### Groups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the unique value groups.</p>


```csharp
public CIMUniqueValueGroup[] Groups { get; set; }
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### LookupStyleset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the lookup styleset.</p>


```csharp
public string LookupStyleset { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default symbol.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinUniqueValueRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


