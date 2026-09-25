# CIMNetworkDatasetTrafficRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Represents a network dataset traffic renderer.</p>


## Object Signature

```csharp
public class CIMNetworkDatasetTrafficRenderer : CIMNetworkDatasetRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkDatasetTrafficRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Represents a network dataset traffic renderer.</p>


```csharp
public CIMNetworkDatasetTrafficRenderer()
```
### Breaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the renderer class breaks.</p>


```csharp
public CIMClassBreak[] Breaks { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkDatasetTrafficRenderer.</p>


```csharp
public CIMNetworkDatasetTrafficRenderer Clone()
```
### DefaultDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the default description.</p>


```csharp
public string DefaultDescription { get; set; }
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### DefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the default symbol.</p>


```csharp
public CIMSymbolReference DefaultSymbol { get; set; }
```
### DrawLineWidthByHierarchyLevelIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to draw line width by hierarchy level index.</p>


```csharp
public bool DrawLineWidthByHierarchyLevelIndex { get; set; }
```
### ExteriorLineWidthIncrement

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the exterior line width increment.</p>


```csharp
public double ExteriorLineWidthIncrement { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkDatasetTrafficRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkDatasetTrafficRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### InteriorLineWidthsByHierarchyLevelIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the interior line widths by hierarchy level index.</p>


```csharp
public double[] InteriorLineWidthsByHierarchyLevelIndex { get; set; }
```
### LineCasingsColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the line casings color.</p>


```csharp
public CIMColor LineCasingsColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScaleFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets the scale filters.</p>


```csharp
public double[] ScaleFilters { get; set; }
```
### ShowLiveTrafficOnly

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show only live traffic.</p>


```csharp
public bool ShowLiveTrafficOnly { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkDatasetTrafficRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseDefaultSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to use the default symbol.</p>


```csharp
public bool UseDefaultSymbol { get; set; }
```
### UseDerivedLineCasingsColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to use a derived line casing color.</p>


```csharp
public bool UseDerivedLineCasingsColor { get; set; }
```
### UseLineCasings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to use line casings.</p>


```csharp
public bool UseLineCasings { get; set; }
```
### UseScaleFilters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to use scale filters.</p>


```csharp
public bool UseScaleFilters { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetTrafficRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


