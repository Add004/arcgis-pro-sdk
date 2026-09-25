# CIMSnappingProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Represents snapping properties.</p>


## Object Signature

```csharp
public class CIMSnappingProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSnappingProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Represents snapping properties.</p>


```csharp
public CIMSnappingProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSnappingProperties.</p>


```csharp
public CIMSnappingProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMSnappingProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMSnappingProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### GeometricFeedbackColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets geometric feedback color.</p>


```csharp
public CIMColor GeometricFeedbackColor { get; set; }
```
### IsZSnappingEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether Z snapping is enabled.</p>


```csharp
public bool IsZSnappingEnabled { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SnapRequestType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets the snap request type.</p>


```csharp
public SnapRequestType SnapRequestType { get; set; }
```
### SnapTipDisplayParts

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the snap tip is fully or partially visible.</p>


```csharp
public int SnapTipDisplayParts { get; set; }
```
### SnapToSketchEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether snapping to the sketch is enabled.</p>


```csharp
public bool SnapToSketchEnabled { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSnappingProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisualFeedbackColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets the visual feedback color.</p>


```csharp
public CIMColor VisualFeedbackColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XYTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets the XY tolerance.</p>


```csharp
public double XYTolerance { get; set; }
```
### XYToleranceUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets the XY tolerance unit.</p>


```csharp
public SnapXYToleranceUnit XYToleranceUnit { get; set; }
```
### ZTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets the Z tolerance.</p>


```csharp
public double ZTolerance { get; set; }
```
### ZToleranceEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSnappingProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether Z tolerance is enabled.</p>


```csharp
public bool ZToleranceEnabled { get; set; }
```


