# CIMDotDensityRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Depicts numeric values as a quantity of dots drawn within polygon features.</p>


## Object Signature

```csharp
public class CIMDotDensityRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDotDensityRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Depicts numeric values as a quantity of dots drawn within polygon features.</p>


```csharp
public CIMDotDensityRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDotDensityRenderer.</p>


```csharp
public CIMDotDensityRenderer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DotDensitySymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the dot density symbol. This is a polygon symbol with multiple layers.
Fill and stroke layers are used to display the underlying polygon, while a marker layer
is used for the actual dot representing a field value.</p>


```csharp
public CIMSymbolReference DotDensitySymbol { get; set; }
```
### DotSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the dot size.</p>


```csharp
public double DotSize { get; set; }
```
### DotValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the dot value.</p>


```csharp
public double DotValue { get; set; }
```
### ExcludeDotsFromMaskedArea

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the exclude dots from masked areas.</p>


```csharp
public bool ExcludeDotsFromMaskedArea { get; set; }
```
### ExclusionClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion clause.</p>


```csharp
public string ExclusionClause { get; set; }
```
### ExclusionDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion description.</p>


```csharp
public string ExclusionDescription { get; set; }
```
### ExclusionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion label.</p>


```csharp
public string ExclusionLabel { get; set; }
```
### ExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the exclusion symbol.</p>


```csharp
public CIMSymbolReference ExclusionSymbol { get; set; }
```
### ExclusionSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the exclusion symbol.</p>


```csharp
public CIMLegendPatch ExclusionSymbolCustomPatch { get; set; }
```
### ExclusionSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the exclusion symbol.</p>


```csharp
public PatchShape ExclusionSymbolPatch { get; set; }
```
### FieldLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the label for each selected field name.</p>


```csharp
public string[] FieldLabels { get; set; }
```
### FieldNames

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the field names dot data comes from.</p>


```csharp
public string[] FieldNames { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMDotDensityRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMDotDensityRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaintainDensity

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to maintain density.</p>


```csharp
public bool MaintainDensity { get; set; }
```
### MaskingLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets a path to the layer that supplies masks.</p>


```csharp
public string MaskingLayer { get; set; }
```
### RandomSeed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets a random seed.</p>


```csharp
public int RandomSeed { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the reference scale. If specified, dots are calibrated from this scale.</p>


```csharp
public double ReferenceScale { get; set; }
```
### SampleSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum number of records to sample.</p>


```csharp
public int SampleSize { get; set; }
```
### SymbolLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend label indicating what the symbol is (e.g. &quot;dot&quot;).</p>


```csharp
public string SymbolLabel { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDotDensityRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UnitLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the legend label indicating what the dots represent (e.g. &quot;people&quot;).</p>


```csharp
public string UnitLabel { get; set; }
```
### UseExclusionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the exclusion symbol.</p>


```csharp
public bool UseExclusionSymbol { get; set; }
```
### UseMasking

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use masking.</p>


```csharp
public bool UseMasking { get; set; }
```
### ValueExpressionInfos

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the arcade expressions the dot data comes from. If this array is populated it takes precedence over /// the FieldNames array.</p>


```csharp
public CIMExpressionInfo[] ValueExpressionInfos { get; set; }
```
### VisualVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Gets or sets the visual variables.</p>


```csharp
public CIMVisualVariable[] VisualVariables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDotDensityRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


