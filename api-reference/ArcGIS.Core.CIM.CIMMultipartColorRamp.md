# CIMMultipartColorRamp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Represents a multipart color ramp scheme.</p>


## Object Signature

```csharp
public class CIMMultipartColorRamp : CIMColorRamp, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">A color ramp scheme defined by combining two or more continuous, discrete, or random ramps.</p>


## Members

### CIMMultipartColorRamp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Represents a multipart color ramp scheme.</p>


```csharp
public CIMMultipartColorRamp()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMultipartColorRamp.</p>


```csharp
public CIMMultipartColorRamp Clone()
```
### ColorRamps

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Gets or sets the ordered list of color ramps (also known as schemes) that are combined to build the multipart ramp. Typically these are continuous color ramps.</p>


```csharp
public CIMColorRamp[] ColorRamps { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Reconstructs the CIMMultipartColorRamp with a specified state from a JSON encoding.</p>


```csharp
public static CIMMultipartColorRamp FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMultipartColorRamp and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Weights

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Gets or sets the proportional weight for each color ramp (also known as a color scheme) that make up the multipart ramp. This allows for ramp to ramp transition at specific weight points.</p>


```csharp
public double[] Weights { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultipartColorRamp.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


