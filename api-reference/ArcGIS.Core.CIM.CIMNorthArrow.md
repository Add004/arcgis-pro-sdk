# CIMNorthArrow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNorthArrow.yml" sourcestartlinenumber="1">Represents a north arrow on a page layout.</p>


## Object Signature

```csharp
public abstract class CIMNorthArrow : CIMMapSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNorthArrow()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNorthArrow.yml" sourcestartlinenumber="1">Represents a north arrow on a page layout.</p>


```csharp
protected CIMNorthArrow()
```
### CalibrationAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the calibration angle for a north arrow.</p>


```csharp
public double CalibrationAngle { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNorthArrow.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceLocation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the reference location for a north arrow.</p>


```csharp
public MapPoint ReferenceLocation { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNorthArrow.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


