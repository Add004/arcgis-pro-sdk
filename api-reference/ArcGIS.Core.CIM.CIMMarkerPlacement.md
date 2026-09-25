# CIMMarkerPlacement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacement.yml" sourcestartlinenumber="1">Represents a marker placement.</p>


## Object Signature

```csharp
public abstract class CIMMarkerPlacement : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerPlacement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacement.yml" sourcestartlinenumber="1">Represents a marker placement.</p>


```csharp
protected CIMMarkerPlacement()
```
### PlacePerPart

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to consider individual geometry parts or the whole geometry.</p>


```csharp
public bool PlacePerPart { get; set; }
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacement.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerPlacement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


