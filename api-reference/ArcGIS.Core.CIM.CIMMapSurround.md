# CIMMapSurround

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSurround.yml" sourcestartlinenumber="1">Represents a map surround on a page layout.</p>


## Object Signature

```csharp
public abstract class CIMMapSurround : CIMFrameElement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapSurround()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSurround.yml" sourcestartlinenumber="1">Represents a map surround on a page layout.</p>


```csharp
protected CIMMapSurround()
```
### MapFrame

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSurround.yml" sourcestartlinenumber="1">Gets or sets the map frame associated with the map surround.</p>


```csharp
public string MapFrame { get; set; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSurround.yml" sourcestartlinenumber="1">Gets or sets the maximum scale.</p>


```csharp
public double MaxScale { get; set; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSurround.yml" sourcestartlinenumber="1">Gets or sets the minimum scale.</p>


```csharp
public double MinScale { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSurround.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapSurround.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


