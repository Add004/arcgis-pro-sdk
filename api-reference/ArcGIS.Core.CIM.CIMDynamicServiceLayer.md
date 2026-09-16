# CIMDynamicServiceLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDynamicServiceLayer.yml" sourcestartlinenumber="1">Represents a dynamic service layer.</p>


## Object Signature

```csharp
public abstract class CIMDynamicServiceLayer : CIMServiceLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDynamicServiceLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDynamicServiceLayer.yml" sourcestartlinenumber="1">Represents a dynamic service layer.</p>


```csharp
protected CIMDynamicServiceLayer()
```
### ImageFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDynamicServiceLayer.yml" sourcestartlinenumber="1">Gets or sets the image format.</p>


```csharp
public esriImageFormat ImageFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDynamicServiceLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### UseTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDynamicServiceLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use time.</p>


```csharp
public bool UseTime { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDynamicServiceLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


