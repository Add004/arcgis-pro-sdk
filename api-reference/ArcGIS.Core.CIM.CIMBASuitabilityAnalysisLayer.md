# CIMBASuitabilityAnalysisLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis layer.</p>


## Object Signature

```csharp
public class CIMBASuitabilityAnalysisLayer : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBASuitabilityAnalysisLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis layer.</p>


```csharp
public CIMBASuitabilityAnalysisLayer()
```
### ClassificationTransparency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the classification  transparency.</p>


```csharp
public double ClassificationTransparency { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBASuitabilityAnalysisLayer.</p>


```csharp
public CIMBASuitabilityAnalysisLayer Clone()
```
### CombinationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis combination method.</p>


```csharp
public BACombinationMethod CombinationMethod { get; set; }
```
### Criteria

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis criterion info items.</p>


```csharp
public CIMBASuitabilityAnalysisCriterion[] Criteria { get; set; }
```
### FinalScoreScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis final score scale method.</p>


```csharp
public BAFinalScoreMethod FinalScoreScale { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMBASuitabilityAnalysisLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMBASuitabilityAnalysisLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### OutlineColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the outline color.</p>


```csharp
public CIMColor OutlineColor { get; set; }
```
### OutlineWidth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the outline width.</p>


```csharp
public double OutlineWidth { get; set; }
```
### PreprocessingMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis preprocessing method.</p>


```csharp
public BAPreprocessingMethod PreprocessingMethod { get; set; }
```
### PresetMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis preset method.</p>


```csharp
public BAPresetMethod PresetMethod { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RendererProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis layer renderer properties.</p>


```csharp
public CIMBARendererProperties RendererProperties { get; set; }
```
### ResultsPaneSettings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the results pane settings.</p>


```csharp
public CIMBASuitabilityAnalysisResultsPaneSettings ResultsPaneSettings { get; set; }
```
### SuitabilityAnalysisSubLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis sub-layer.</p>


```csharp
public CIMBASuitabilityAnalysisSubLayer SuitabilityAnalysisSubLayer { get; set; }
```
### TargetSite

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis Target Site.</p>


```csharp
public CIMBASuitabilityAnalysisTargetSiteSubLayer TargetSite { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBASuitabilityAnalysisLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


