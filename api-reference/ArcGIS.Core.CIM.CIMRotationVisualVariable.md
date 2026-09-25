# CIMRotationVisualVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Represents a rotation visual variable.</p>


## Object Signature

```csharp
public class CIMRotationVisualVariable : CIMVisualVariable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRotationVisualVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Represents a rotation visual variable.</p>


```csharp
public CIMRotationVisualVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRotationVisualVariable.</p>


```csharp
public CIMRotationVisualVariable Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMRotationVisualVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMRotationVisualVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### NormalToSurface

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the normal to surface value which applies to 3D views. If true, rotation is applied after marker is rotated normal to the 3D surface. If false, all rotations are applied starting from zeroed X, Y, Z rotation.</p>


```csharp
public bool NormalToSurface { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RotationTypeZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the Z rotation type.</p>


```csharp
public SymbolRotationType RotationTypeZ { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRotationVisualVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisualVariableInfoX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the visual variable info for the X dimension.</p>


```csharp
public CIMVisualVariableInfo VisualVariableInfoX { get; set; }
```
### VisualVariableInfoY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the visual variable info for the Y dimension.</p>


```csharp
public CIMVisualVariableInfo VisualVariableInfoY { get; set; }
```
### VisualVariableInfoZ

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the visual variable info for the Z dimension.</p>


```csharp
public CIMVisualVariableInfo VisualVariableInfoZ { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRotationVisualVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


