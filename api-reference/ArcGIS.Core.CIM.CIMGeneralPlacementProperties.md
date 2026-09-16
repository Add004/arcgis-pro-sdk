# CIMGeneralPlacementProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Represents general placement properties. This is base class for general placement properties for each label engine.</p>


## Object Signature

```csharp
public abstract class CIMGeneralPlacementProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeneralPlacementProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Represents general placement properties. This is base class for general placement properties for each label engine.</p>


```csharp
protected CIMGeneralPlacementProperties()
```
### DrawUnplacedLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to draw unplaced labels.</p>


```csharp
public bool DrawUnplacedLabels { get; set; }
```
### InvertedLabelTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the inverted label tolerance which is the angle at which the label orientation is switched.</p>


```csharp
public double InvertedLabelTolerance { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotateLabelWithDisplay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not rotate labels when the display rotates.</p>


```csharp
public bool RotateLabelWithDisplay { get; set; }
```
### UnplacedLabelColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Gets or sets the unplaced label color.</p>


```csharp
public CIMColor UnplacedLabelColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeneralPlacementProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


