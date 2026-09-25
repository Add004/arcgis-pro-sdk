# CIMMarkerStrokePlacement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerStrokePlacement.yml" sourcestartlinenumber="1">Represents a marker stroke placement.</p>


## Object Signature

```csharp
public abstract class CIMMarkerStrokePlacement : CIMMarkerPlacement, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerStrokePlacement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerStrokePlacement.yml" sourcestartlinenumber="1">Represents a marker stroke placement.</p>


```csharp
protected CIMMarkerStrokePlacement()
```
### AngleToLine

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerStrokePlacement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to angle the marker to the line.</p>


```csharp
public bool AngleToLine { get; set; }
```
### KeepUpright

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerStrokePlacement.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to keep the marker upright.
This is only considered if AngleToLine is true.</p>


```csharp
public bool KeepUpright { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerStrokePlacement.yml" sourcestartlinenumber="1">Gets or sets the offset.</p>


```csharp
public double Offset { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerStrokePlacement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerStrokePlacement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


