# CIMPointCloudRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Represents a point cloud renderer.</p>


## Object Signature

```csharp
public abstract class CIMPointCloudRenderer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPointCloudRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Represents a point cloud renderer.</p>


```csharp
protected CIMPointCloudRenderer()
```
### ColorModulation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Gets or sets the filter used to filter the points being drawn.</p>


```csharp
public CIMColorModulationInfo ColorModulation { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Gets or sets the field used to render the points.</p>


```csharp
public string Field { get; set; }
```
### FieldTransformType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Gets or sets the field transform type.</p>


```csharp
public PointCloudFieldTransformType FieldTransformType { get; set; }
```
### PointShape

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Gets or sets the symbol type.</p>


```csharp
public PointCloudShapeType PointShape { get; set; }
```
### PointSizeAlgorithm

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Gets or sets the algorithm used to determine the symbol size.</p>


```csharp
public CIMPointCloudAlgorithm PointSizeAlgorithm { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPointCloudRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


