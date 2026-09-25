# CIMGeometricEffectWave

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Represents the wave geometric effect which creates a dynamic line or polygon along a feature with a repeating wave pattern.</p>


## Object Signature

```csharp
public class CIMGeometricEffectWave : CIMGeometricEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometricEffectWave()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Represents the wave geometric effect which creates a dynamic line or polygon along a feature with a repeating wave pattern.</p>


```csharp
public CIMGeometricEffectWave()
```
### Amplitude

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Gets or sets the distance perpendicular to a feature to display the curves for the symbol.</p>


```csharp
public double Amplitude { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometricEffectWave.</p>


```csharp
public CIMGeometricEffectWave Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometricEffectWave with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometricEffectWave FromJson(string json, JsonDeserializationSettings settings = null)
```
### Period

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Gets or sets the distance along the line or polygon to display the curves for the symbol.</p>


```csharp
public double Period { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Seed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Gets or sets the staring value for generating a random number. This is only used when the Waveform is set to Random.</p>


```csharp
public int Seed { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometricEffectWave and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Waveform

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Gets or sets the shape of the curves to be displayed along the symbol.</p>


```csharp
public GeometricEffectWaveform Waveform { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometricEffectWave.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


