# CIMTinRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinRenderer.yml" sourcestartlinenumber="1">Represents a TIN renderer.</p>


## Object Signature

```csharp
public abstract class CIMTinRenderer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinRenderer.yml" sourcestartlinenumber="1">Represents a TIN renderer.</p>


```csharp
protected CIMTinRenderer()
```
### Illuminate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to illuminate.</p>


```csharp
public bool Illuminate { get; set; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum scale for renderer draw (set as the denominator of the scale's representative fraction).
Values less than or equal to 0 indicate there is no maximum scale and the renderer will draw at any scale above the minimum.</p>


```csharp
public double MaxScale { get; set; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinRenderer.yml" sourcestartlinenumber="1">Gets or sets the minimum scale for renderer draw (set as the denominator of the scale's representative fraction).
Values less than or equal to 0 indicate there is no minimum scale and the renderer will draw at any scale below the maximum.</p>


```csharp
public double MinScale { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


