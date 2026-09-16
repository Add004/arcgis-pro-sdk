# CIMProportionalRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Represents a proportional renderer.</p>


## Object Signature

```csharp
public class CIMProportionalRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProportionalRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Represents a proportional renderer.</p>


```csharp
public CIMProportionalRenderer()
```
### AuthoringInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the additional authoring information used by the renderer.</p>


```csharp
public CIMProportionalRendererAuthoringInfo AuthoringInfo { get; set; }
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets background symbol features are drawn with underneath the proportional symbols.</p>


```csharp
public CIMSymbolReference BackgroundSymbol { get; set; }
```
### BarrierWeight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the barrier weight used for graduated symbols to avoid labels.</p>


```csharp
public BarrierWeight BarrierWeight { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProportionalRenderer.</p>


```csharp
public CIMProportionalRenderer Clone()
```
### DefaultDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the default description.</p>


```csharp
public string DefaultDescription { get; set; }
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### DefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the default symbol.</p>


```csharp
public CIMSymbolReference DefaultSymbol { get; set; }
```
### DefaultSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the default symbol.</p>


```csharp
public CIMLegendPatch DefaultSymbolCustomPatch { get; set; }
```
### DefaultSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the default symbol.</p>


```csharp
public PatchShape DefaultSymbolPatch { get; set; }
```
### DrawProportionalSymbolsAboveAllLayers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to draw proportional symbols for polygon features above all layers.</p>


```csharp
public bool DrawProportionalSymbolsAboveAllLayers { get; set; }
```
### ExclusionClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion clause.</p>


```csharp
public string ExclusionClause { get; set; }
```
### ExclusionDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion description.</p>


```csharp
public string ExclusionDescription { get; set; }
```
### ExclusionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion label.</p>


```csharp
public string ExclusionLabel { get; set; }
```
### ExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion symbol.</p>


```csharp
public CIMSymbolReference ExclusionSymbol { get; set; }
```
### ExclusionSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the exclusion symbol.</p>


```csharp
public CIMLegendPatch ExclusionSymbolCustomPatch { get; set; }
```
### ExclusionSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the exclusion symbol.</p>


```csharp
public PatchShape ExclusionSymbolPatch { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the field the renderer is using.</p>


```csharp
public string Field { get; set; }
```
### FlanneryCompensation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use Flannery compensation.</p>


```csharp
public bool FlanneryCompensation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMProportionalRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMProportionalRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### LegendSymbolCount

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend symbol count.</p>


```csharp
public int LegendSymbolCount { get; set; }
```
### MaxDataValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum data value.</p>


```csharp
public double MaxDataValue { get; set; }
```
### MinDataValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the minimum data value.</p>


```csharp
public double MinDataValue { get; set; }
```
### MinSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the minimum symbol.</p>


```csharp
public CIMSymbolReference MinSymbol { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationTotal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization total.</p>


```csharp
public double NormalizationTotal { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the normalization type.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SampleSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum number of records to sample.</p>


```csharp
public int SampleSize { get; set; }
```
### ShowInAscendingOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show classes in ascending order.</p>


```csharp
public bool ShowInAscendingOrder { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProportionalRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UnitSymbolization

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the unit symbolization.</p>


```csharp
public CIMUnitSymbolization UnitSymbolization { get; set; }
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default symbol.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```
### UseExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the exclusion symbol.</p>


```csharp
public bool UseExclusionSymbol { get; set; }
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a number. When both Fields and ValueExpressionInfo are present ValueExpressionInfo is used.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### VisualVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Gets or sets the visual variables.</p>


```csharp
public CIMVisualVariable[] VisualVariables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


