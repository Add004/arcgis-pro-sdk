# CIMServiceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Represents a service layer.</p>


## Object Signature

```csharp
public abstract class CIMServiceLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMServiceLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Represents a service layer.</p>


```csharp
protected CIMServiceLayer()
```
### BackgroundColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the background color.</p>


```csharp
public CIMColor BackgroundColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServiceConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the service connection.</p>


```csharp
public CIMServiceConnection ServiceConnection { get; set; }
```
### SubLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the sublayers.</p>


```csharp
public CIMSubLayerBase[] SubLayers { get; set; }
```
### SubTables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the subtables.</p>


```csharp
public CIMServiceSubTable[] SubTables { get; set; }
```
### TransparentColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the transparent color.</p>


```csharp
public CIMColor TransparentColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMServiceLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


