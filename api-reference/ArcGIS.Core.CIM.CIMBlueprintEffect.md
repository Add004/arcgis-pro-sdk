# CIMBlueprintEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a blueprint style.</p>


## Object Signature

```csharp
public class CIMBlueprintEffect : CIMVisualEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBlueprintEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Represents a visual effect for reshading the scene with a blueprint style.</p>


```csharp
public CIMBlueprintEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBlueprintEffect.</p>


```csharp
public CIMBlueprintEffect Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMBlueprintEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMBlueprintEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridSize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Gets or sets the size of the background grid in points.</p>


```csharp
public double GridSize { get; set; }
```
### GridSubdivisions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Gets or sets the number of width and height subdivisions for each cell in the grid.</p>


```csharp
public int GridSubdivisions { get; set; }
```
### OutlineStrength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Gets or sets the outline strength which influences the outline weight and the threshold used for edge detection.</p>


```csharp
public double OutlineStrength { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBlueprintEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBlueprintEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


