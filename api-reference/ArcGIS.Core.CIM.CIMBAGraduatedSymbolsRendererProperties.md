# CIMBAGraduatedSymbolsRendererProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer graduated symbol renderer properties.</p>


## Object Signature

```csharp
public class CIMBAGraduatedSymbolsRendererProperties : CIMBARendererProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBAGraduatedSymbolsRendererProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Represents Business Analyst Color Coded Layer graduated symbol renderer properties.</p>


```csharp
public CIMBAGraduatedSymbolsRendererProperties()
```
### ClassificationFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the classification field names in the levels of detail feature classes.</p>


```csharp
public string[] ClassificationFields { get; set; }
```
### ClassificationMethod

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the classification method.</p>


```csharp
public ClassificationMethod ClassificationMethod { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBAGraduatedSymbolsRendererProperties.</p>


```csharp
public CIMBAGraduatedSymbolsRendererProperties Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMBAGraduatedSymbolsRendererProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMBAGraduatedSymbolsRendererProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the maximum symbol size.</p>


```csharp
public double MaxSymbolSize { get; set; }
```
### MinSymbolSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the minimum symbol size.</p>


```csharp
public double MinSymbolSize { get; set; }
```
### NumBreaks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the number of breaks for classification renderer.</p>


```csharp
public int NumBreaks { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandardDeviationMultiplier

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the standard deviation multiplier. Used to compute breaks for the standard deviation classification method.</p>


```csharp
public StandardDeviationMultiplier StandardDeviationMultiplier { get; set; }
```
### TemplateColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Gets or sets the template color. Used for layers with a single variable.</p>


```csharp
public CIMColor TemplateColor { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBAGraduatedSymbolsRendererProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBAGraduatedSymbolsRendererProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


