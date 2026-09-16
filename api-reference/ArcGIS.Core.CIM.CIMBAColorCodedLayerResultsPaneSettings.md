# CIMBAColorCodedLayerResultsPaneSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Color Coded Layer Results Pane settings.</p>


## Object Signature

```csharp
public class CIMBAColorCodedLayerResultsPaneSettings : CIMBAResultsPaneSettings, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAColorCodedLayerResultsPaneSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Represents Color Coded Layer Results Pane settings.</p>


```csharp
public CIMBAColorCodedLayerResultsPaneSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAColorCodedLayerResultsPaneSettings.</p>


```csharp
public CIMBAColorCodedLayerResultsPaneSettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMBAColorCodedLayerResultsPaneSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAColorCodedLayerResultsPaneSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### HistogramVariable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the variable name for the histogram chart.</p>


```csharp
public string HistogramVariable { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScatterplotXAxisVariableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the variable name for the X-Axis of the scatterplot chart.</p>


```csharp
public string ScatterplotXAxisVariableName { get; set; }
```
### ScatterplotYAxisVariableName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets the variable name for the Y-Axis of the scatterplot chart.</p>


```csharp
public string ScatterplotYAxisVariableName { get; set; }
```
### ShowRegressionLineOnScatterplot

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the regression line should be shown on the scatterplot chart.</p>


```csharp
public bool ShowRegressionLineOnScatterplot { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAColorCodedLayerResultsPaneSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAColorCodedLayerResultsPaneSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


