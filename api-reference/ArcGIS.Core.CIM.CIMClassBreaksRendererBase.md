# CIMClassBreaksRendererBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">The base class for class breaks renderer types.</p>


## Object Signature

```csharp
public abstract class CIMClassBreaksRendererBase : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMClassBreaksRendererBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">The base class for class breaks renderer types.</p>


```csharp
protected CIMClassBreaksRendererBase()
```
### AlwaysUpdateClassLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to automatically update class labels whenever a class upper value is changed.</p>


```csharp
public bool AlwaysUpdateClassLabels { get; set; }
```
### AuthoringInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the additional authoring information used by the renderer.</p>


```csharp
public CIMClassBreaksRendererAuthoringInfo AuthoringInfo { get; set; }
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the background symbol used for graduated symbols.</p>


```csharp
public CIMSymbolReference BackgroundSymbol { get; set; }
```
### BarrierWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the barrier weight used for graduated symbols to avoid labels.</p>


```csharp
public BarrierWeight BarrierWeight { get; set; }
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the class breaks.</p>


```csharp
public CIMClassBreak[] Breaks { get; set; }
```
### ClassBreakType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the class break type.</p>


```csharp
public ClassBreakType ClassBreakType { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DefaultDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the default description.</p>


```csharp
public string DefaultDescription { get; set; }
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### DefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the default symbol.</p>


```csharp
public CIMSymbolReference DefaultSymbol { get; set; }
```
### DefaultSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the default symbol.</p>


```csharp
public CIMLegendPatch DefaultSymbolCustomPatch { get; set; }
```
### DefaultSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the default symbol.</p>


```csharp
public PatchShape DefaultSymbolPatch { get; set; }
```
### DrawGraduatedSymbolsAboveAllLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to draw graduated symbols for polygon features above all layers.</p>


```csharp
public bool DrawGraduatedSymbolsAboveAllLayers { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the field for rendering.</p>


```csharp
public string Field { get; set; }
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the minimum break.</p>


```csharp
public double MinimumBreak { get; set; }
```
### MinimumLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the minimum label.</p>


```csharp
public string MinimumLabel { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### PolygonSymbolColorTarget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the property that controls how the color ramp is applied to polygon symbols.</p>


```csharp
public PolygonSymbolColorTarget PolygonSymbolColorTarget { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SampleSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets the maximum number of records to sample.</p>


```csharp
public int SampleSize { get; set; }
```
### ShowClassGaps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show class gaps.</p>


```csharp
public bool ShowClassGaps { get; set; }
```
### ShowInAscendingOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show classes in ascending order.</p>


```csharp
public bool ShowInAscendingOrder { get; set; }
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default symbol.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a number. When both Fields and ValueExpressionInfo are present ValueExpressionInfo is used.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMClassBreaksRendererBase.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


