# CIMFloodSimulationObject

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationObject.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation object.</p>


## Object Signature

```csharp
public abstract class CIMFloodSimulationObject : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationObject()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationObject.yml" sourcestartlinenumber="1">Provides access to properties of a flood simulation object.</p>


```csharp
protected CIMFloodSimulationObject()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationObject.yml" sourcestartlinenumber="1">Gets or sets the name of the object. It holds the layer URI when a raster is used. Otherwise it holds the displayed value.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationObject.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationObject.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the object is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationObject.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


