# CIMLASDatasetLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Represents a LAS dataset layer.</p>


## Object Signature

```csharp
public class CIMLASDatasetLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLASDatasetLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Represents a LAS dataset layer.</p>


```csharp
public CIMLASDatasetLayer()
```
### AnalysisToolsResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the analysis tool resolution.</p>


```csharp
public double AnalysisToolsResolution { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLASDatasetLayer.</p>


```csharp
public CIMLASDatasetLayer Clone()
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the LAS dataset.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the display field.</p>


```csharp
public string DisplayField { get; set; }
```
### EyeDomeLighting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets eye-dome lighting properties.</p>


```csharp
public CIMEyeDomeLighting EyeDomeLighting { get; set; }
```
### FileExtentSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the file extent symbol.</p>


```csharp
public CIMSymbolReference FileExtentSymbol { get; set; }
```
### FileNameSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the file name symbol.</p>


```csharp
public CIMSymbolReference FileNameSymbol { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMLASDatasetLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMLASDatasetLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### FullResolutionScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the full resolution scale.</p>


```csharp
public double FullResolutionScale { get; set; }
```
### IsFlattened

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer is flattened.</p>


```csharp
public bool IsFlattened { get; set; }
```
### LASDatasetFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the LAS dataset filter.</p>


```csharp
public LasFilter LASDatasetFilter { get; set; }
```
### MaintainCurrentSurface

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the current surface should be maintained.</p>


```csharp
public bool MaintainCurrentSurface { get; set; }
```
### PointBudget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the point budget.</p>


```csharp
public int PointBudget { get; set; }
```
### PointCountPerCentimeter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the point count per centimeter.</p>


```csharp
public int PointCountPerCentimeter { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the renderers.</p>


```csharp
public CIMTinRenderer[] Renderers { get; set; }
```
### ScaleSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to scale symbols.</p>


```csharp
public bool ScaleSymbols { get; set; }
```
### Selectable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is selectable.</p>


```csharp
public bool Selectable { get; set; }
```
### SelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets the selection color.</p>


```csharp
public CIMColor SelectionColor { get; set; }
```
### ShowFileExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the file extent.</p>


```csharp
public bool ShowFileExtent { get; set; }
```
### ShowFileName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the file name.</p>


```csharp
public bool ShowFileName { get; set; }
```
### ShowResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the resolution.</p>


```csharp
public bool ShowResolution { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLASDatasetLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseDynamicLOD

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use dynamic level-of-detail.</p>


```csharp
public bool UseDynamicLOD { get; set; }
```
### UseFullResolutionScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the full resolution scale.</p>


```csharp
public bool UseFullResolutionScale { get; set; }
```
### UseSelectionColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use the selection color.</p>


```csharp
public bool UseSelectionColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASDatasetLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


