# CIMSubLayerBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Represents sublayer base class.</p>


## Object Signature

```csharp
public abstract class CIMSubLayerBase : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSubLayerBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Represents sublayer base class.</p>


```csharp
protected CIMSubLayerBase()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets the description.</p>


```csharp
public string Description { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets the maximum scale for layer draw (set as the denominator of the scale's representative fraction).</p>


```csharp
public double MaxScale { get; set; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets the minimum scale for layer draw (set as the denominator of the scale's representative fraction).</p>


```csharp
public double MinScale { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServiceLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets identifier that will be used to identify the layer in server.</p>


```csharp
public int ServiceLayerID { get; set; }
```
### ShowLegends

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show legends.</p>


```csharp
public bool ShowLegends { get; set; }
```
### SubLayerID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets the unique identifier for this sublayer within its layer. Set by the system and typically a number.</p>


```csharp
public string SubLayerID { get; set; }
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this layer is visible.</p>


```csharp
public bool Visibility { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSubLayerBase.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


