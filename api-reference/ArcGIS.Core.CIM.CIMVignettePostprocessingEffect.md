# CIMVignettePostprocessingEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Represents a post-processing technique that reshades the scene with a vignette effect.</p>


## Object Signature

```csharp
public class CIMVignettePostprocessingEffect : CIMPostprocessingEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVignettePostprocessingEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Represents a post-processing technique that reshades the scene with a vignette effect.</p>


```csharp
public CIMVignettePostprocessingEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVignettePostprocessingEffect.</p>


```csharp
public CIMVignettePostprocessingEffect Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMVignettePostprocessingEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMVignettePostprocessingEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Size

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Gets or sets the percentage of the view effected by the vignette effect.</p>


```csharp
public double Size { get; set; }
```
### Strength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Gets or sets the strength of the vignette effect.</p>


```csharp
public double Strength { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVignettePostprocessingEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVignettePostprocessingEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


