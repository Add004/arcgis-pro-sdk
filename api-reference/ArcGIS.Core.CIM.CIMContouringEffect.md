# CIMContouringEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Represents a surface effect for adding contour lines to surfaces in 3D views.</p>


## Object Signature

```csharp
public class CIMContouringEffect : CIMSurfaceEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMContouringEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Represents a surface effect for adding contour lines to surfaces in 3D views.</p>


```csharp
public CIMContouringEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMContouringEffect.</p>


```csharp
public CIMContouringEffect Clone()
```
### Distance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Gets or sets maximum distance for which the effect should be active measured in meters.</p>


```csharp
public double Distance { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMContouringEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMContouringEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Thickness

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Gets or sets the thickness of the contour lines measured in meters or points depending on the value of UseRealWorldSizeThickness.</p>


```csharp
public double Thickness { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMContouringEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseRealWorldSizeThickness

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether thickness should be measured in meters when true or measured in points when false.</p>


```csharp
public bool UseRealWorldSizeThickness { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContouringEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


