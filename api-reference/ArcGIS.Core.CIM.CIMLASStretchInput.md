# CIMLASStretchInput

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Represents LAS stretch input.</p>


## Object Signature

```csharp
public class CIMLASStretchInput : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLASStretchInput()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Represents LAS stretch input.</p>


```csharp
public CIMLASStretchInput()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLASStretchInput.</p>


```csharp
public CIMLASStretchInput Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Reconstructs the CIMLASStretchInput with a specified state from a JSON encoding.</p>


```csharp
public static CIMLASStretchInput FromJson(string json, JsonDeserializationSettings settings = null)
```
### GammaValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the gamma value.</p>


```csharp
public double GammaValue { get; set; }
```
### Invert

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to invert the stretch.</p>


```csharp
public bool Invert { get; set; }
```
### Lookup

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the lookup values.</p>


```csharp
public int[] Lookup { get; set; }
```
### MaxPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the maximum percent.</p>


```csharp
public double MaxPercent { get; set; }
```
### MinPercent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the minimum percent.</p>


```csharp
public double MinPercent { get; set; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the number format.</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandardDeviationParam

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the standard deviation parameter.</p>


```csharp
public double StandardDeviationParam { get; set; }
```
### StatsType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the LAS stats type.</p>


```csharp
public LASStretchStatsType StatsType { get; set; }
```
### StretchAttribute

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the LAS stretch attribute.</p>


```csharp
public LASStretchAttribute StretchAttribute { get; set; }
```
### StretchClasses

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the stretch classes.</p>


```csharp
public CIMLASStretchClass[] StretchClasses { get; set; }
```
### StretchMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the stretch max.</p>


```csharp
public double StretchMax { get; set; }
```
### StretchMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the stretch min.</p>


```csharp
public double StretchMin { get; set; }
```
### StretchStats

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the stretch statistics.</p>


```csharp
public StatsHistogram StretchStats { get; set; }
```
### StretchType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets the stretch type.</p>


```csharp
public LASStretchType StretchType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLASStretchInput and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseCustomStretchMinMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use custom stretch minimum maximum.</p>


```csharp
public bool UseCustomStretchMinMax { get; set; }
```
### UseGammaStretch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to use gamma stretch.</p>


```csharp
public bool UseGammaStretch { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLASStretchInput.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


