# CIMVoxelUniqueValueRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a unique value renderer.</p>


## Object Signature

```csharp
public class CIMVoxelUniqueValueRenderer : CIMVoxelRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVoxelUniqueValueRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Represents a unique value renderer.</p>


```csharp
public CIMVoxelUniqueValueRenderer()
```
### Classes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the unique color classes of the renderer.</p>


```csharp
public CIMVoxelColorUniqueValue[] Classes { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVoxelUniqueValueRenderer.</p>


```csharp
public CIMVoxelUniqueValueRenderer Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the color ramp.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DefaultColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the default color.</p>


```csharp
public CIMColor DefaultColor { get; set; }
```
### DefaultDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the default description.</p>


```csharp
public string DefaultDescription { get; set; }
```
### DefaultLabel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the default label.</p>


```csharp
public string DefaultLabel { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMVoxelUniqueValueRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMVoxelUniqueValueRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the heading.</p>


```csharp
public string Heading { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowClassVisibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the class visibility is shown in the contents pane.</p>


```csharp
public bool ShowClassVisibility { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVoxelUniqueValueRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UnlistedValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets the unlisted values.</p>


```csharp
public int[] UnlistedValues { get; set; }
```
### UseDefaultColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether of not to use the default color.</p>


```csharp
public bool UseDefaultColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVoxelUniqueValueRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


