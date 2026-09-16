# CIMBAGraduatedColorsRendererProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer graduated colors renderer properties.</p>


## Object Signature

```csharp
public class CIMBAGraduatedColorsRendererProperties : CIMBARendererProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAGraduatedColorsRendererProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer graduated colors renderer properties.</p>


```csharp
public CIMBAGraduatedColorsRendererProperties()
```
### ClassificationField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the classification field name in the levels of detail feature classes.</p>


```csharp
public string ClassificationField { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAGraduatedColorsRendererProperties.</p>


```csharp
public CIMBAGraduatedColorsRendererProperties Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMBAGraduatedColorsRendererProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAGraduatedColorsRendererProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### NumBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the number of breaks for classification renderer.</p>


```csharp
public int NumBreaks { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandardDeviationMultiplier

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the standard deviation multiplier. Used to compute breaks for the standard deviation classification method.</p>


```csharp
public StandardDeviationMultiplier StandardDeviationMultiplier { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAGraduatedColorsRendererProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedColorsRendererProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


