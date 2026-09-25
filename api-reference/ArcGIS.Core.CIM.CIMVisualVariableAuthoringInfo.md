# CIMVisualVariableAuthoringInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Represents visual variable metadata used for authoring.</p>


## Object Signature

```csharp
public class CIMVisualVariableAuthoringInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVisualVariableAuthoringInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Represents visual variable metadata used for authoring.</p>


```csharp
public CIMVisualVariableAuthoringInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVisualVariableAuthoringInfo.</p>


```csharp
public CIMVisualVariableAuthoringInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMVisualVariableAuthoringInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMVisualVariableAuthoringInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the legend heading.</p>


```csharp
public string Heading { get; set; }
```
### MaxSliderValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the maximum value.</p>


```csharp
public double MaxSliderValue { get; set; }
```
### MinSliderValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the minimum value.</p>


```csharp
public double MinSliderValue { get; set; }
```
### NumberOfHistogramBins

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the number of bins displayed in the histogram.</p>


```csharp
public int NumberOfHistogramBins { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowLegend

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show legends.</p>


```csharp
public bool ShowLegend { get; set; }
```
### Theme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets a theme as an array of strings.</p>


```csharp
public string Theme { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVisualVariableAuthoringInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableAuthoringInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


