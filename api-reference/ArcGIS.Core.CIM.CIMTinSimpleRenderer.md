# CIMTinSimpleRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinSimpleRenderer.yml" sourcestartlinenumber="1">Represents a TIN simple renderer.</p>


## Object Signature

```csharp
public abstract class CIMTinSimpleRenderer : CIMTinRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinSimpleRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinSimpleRenderer.yml" sourcestartlinenumber="1">Represents a TIN simple renderer.</p>


```csharp
protected CIMTinSimpleRenderer()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the label.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinSimpleRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinSimpleRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinSimpleRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


