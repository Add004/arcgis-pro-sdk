# CIMRasterClassifyColorizer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Represents a raster classify colorizer.</p>


## Object Signature

```csharp
public class CIMRasterClassifyColorizer : CIMRasterColorizer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterClassifyColorizer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Represents a raster classify colorizer.</p>


```csharp
public CIMRasterClassifyColorizer()
```
### AlwaysUpdateClassLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to automatically update class labels whenever a class upper value is changed.</p>


```csharp
public bool AlwaysUpdateClassLabels { get; set; }
```
### ClassBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the class breaks of the renderer.</p>


```csharp
public CIMRasterClassBreak[] ClassBreaks { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterClassifyColorizer.</p>


```csharp
public CIMRasterClassifyColorizer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### ExclusionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the exclusion color.</p>


```csharp
public CIMColor ExclusionColor { get; set; }
```
### ExclusionDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the exclusion description.</p>


```csharp
public string ExclusionDescription { get; set; }
```
### ExclusionLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the exclusion label.</p>


```csharp
public string ExclusionLabel { get; set; }
```
### ExclusionRanges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the exclusion ranges as an array of doubles.</p>


```csharp
public double[] ExclusionRanges { get; set; }
```
### ExclusionValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the exclusion values as an array of doubles.</p>


```csharp
public double[] ExclusionValues { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the renderer field.</p>


```csharp
public string Field { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterClassifyColorizer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterClassifyColorizer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the legend heading.</p>


```csharp
public string Heading { get; set; }
```
### MinimumBreak

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the minimum break of the classification.</p>


```csharp
public double MinimumBreak { get; set; }
```
### NormalizationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the normalization field.</p>


```csharp
public string NormalizationField { get; set; }
```
### NormalizationTotal

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the normalization total.</p>


```csharp
public double NormalizationTotal { get; set; }
```
### NormalizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the normalization type.</p>


```csharp
public DataNormalizationMethod NormalizationType { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets the number format applied to values.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowClassGaps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show class gaps.</p>


```csharp
public bool ShowClassGaps { get; set; }
```
### ShowInAscendingOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show classes in ascending order.</p>


```csharp
public bool ShowInAscendingOrder { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterClassifyColorizer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseExclusionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the exclusion color.</p>


```csharp
public bool UseExclusionColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterClassifyColorizer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


