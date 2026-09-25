# CIMUniqueValueRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a unique value renderer.</p>


## Object Signature

```csharp
public class CIMUniqueValueRenderer : CIMRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMUniqueValueRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a unique value renderer.</p>


```csharp
public CIMUniqueValueRenderer()
```
### AuthoringInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the property that controls how the color ramp is applied to polygon symbols.</p>


```csharp
public CIMUniqueValueRendererAuthoringInfo AuthoringInfo { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMUniqueValueRenderer.</p>


```csharp
public CIMUniqueValueRenderer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DefaultDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the default description.</p>


```csharp
public string DefaultDescription { get; set; }
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### DefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the default symbol.</p>


```csharp
public CIMSymbolReference DefaultSymbol { get; set; }
```
### DefaultSymbolCustomPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the custom patch for the default symbol.</p>


```csharp
public CIMLegendPatch DefaultSymbolCustomPatch { get; set; }
```
### DefaultSymbolPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the patch shape for the default symbol.</p>


```csharp
public PatchShape DefaultSymbolPatch { get; set; }
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the fields used by this renderer.</p>


```csharp
public string[] Fields { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMUniqueValueRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMUniqueValueRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Groups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the unique value groups.</p>


```csharp
public CIMUniqueValueGroup[] Groups { get; set; }
```
### IsDefaultSymbolVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not the default symbol is visible.</p>


```csharp
public bool IsDefaultSymbolVisible { get; set; }
```
### PolygonSymbolColorTarget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the property that controls how the color ramp is applied to polygon symbols.</p>


```csharp
public PolygonSymbolColorTarget PolygonSymbolColorTarget { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SampleSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the maximum number of records to sample.</p>


```csharp
public int SampleSize { get; set; }
```
### ShowClassVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the class visibility is shown in the contents pane.</p>


```csharp
public bool ShowClassVisibility { get; set; }
```
### StyleGallery

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the style item name for the color ramp.</p>


```csharp
public string StyleGallery { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMUniqueValueRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default symbol.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```
### ValueExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets ExpressionInfo that contains the Arcade expression that returns value as a string. When both Fields and ValueExpressionInfo are present ValueExpressionInfo is used.</p>


```csharp
public CIMExpressionInfo ValueExpressionInfo { get; set; }
```
### VisualVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the visual variables.</p>


```csharp
public CIMVisualVariable[] VisualVariables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMUniqueValueRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


