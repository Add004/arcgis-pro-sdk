# CIMAnnotationLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Represents an annotation layer used to draw annotation feature classes.</p>


## Object Signature

```csharp
public class CIMAnnotationLayer : CIMBasicFeatureLayer, INotifyPropertyChanged, IXmlSerializable, ICIMBasicFeatureLayer
```


## Members

### CIMAnnotationLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Represents an annotation layer used to draw annotation feature classes.</p>


```csharp
public CIMAnnotationLayer()
```
### BarrierWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets the weight of features in this layer when considered as barriers to labeling.</p>


```csharp
public BarrierWeight BarrierWeight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAnnotationLayer.</p>


```csharp
public CIMAnnotationLayer Clone()
```
### DrawGeometry

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the geometry of the text graphics should be drawn.</p>


```csharp
public bool DrawGeometry { get; set; }
```
### DrawGeometryLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets the line symbol used to draw text graphic line geometries when the DrawGeometry option is true.</p>


```csharp
public CIMSymbolReference DrawGeometryLineSymbol { get; set; }
```
### DrawGeometryPointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets the point symbol used to draw text graphic line geometries when the DrawGeometry option is true.</p>


```csharp
public CIMSymbolReference DrawGeometryPointSymbol { get; set; }
```
### DrawUnplacedAnnotation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether unplaced annotation should be drawn.</p>


```csharp
public bool DrawUnplacedAnnotation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMAnnotationLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMAnnotationLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### InlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets the in-line color. When using the SymbolSubstitutionIndividualSubordinate or SymbolSubstitutionIndividualDominant substitution types this is the color that all text graphics that are stored in-line (bloated) will be overridden with.</p>


```csharp
public CIMColor InlineColor { get; set; }
```
### MassColorSubstitute

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets the mass color substitute. When using the SymbolSubstitutionColor substitution type this is the color that all text graphics will be overridden with.</p>


```csharp
public CIMColor MassColorSubstitute { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets a collection of AnnotationSubLayers, corresponding to the annotation subclasses defined by the annotation feature class.</p>


```csharp
public CIMAnnotationSubLayer[] SubLayers { get; set; }
```
### SubstitutionSymbolCollection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets a symbol substitution collection.</p>


```csharp
public CIMSymbolIdentifier[] SubstitutionSymbolCollection { get; set; }
```
### SymbolSubstitutionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets the type of symbol substitution this layer uses.</p>


```csharp
public SymbolSubstitutionType SymbolSubstitutionType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAnnotationLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UnplacedAnnotationColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Gets or sets the color that unplaced text graphics will be drawn with when Unplaced Annotation is drawn.</p>


```csharp
public CIMColor UnplacedAnnotationColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAnnotationLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


