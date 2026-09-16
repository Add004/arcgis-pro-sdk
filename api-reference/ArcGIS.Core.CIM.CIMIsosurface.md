# CIMIsosurface

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Represents a isosurface.</p>


## Object Signature

```csharp
public class CIMIsosurface : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMIsosurface()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Represents a isosurface.</p>


```csharp
public CIMIsosurface()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Creates a deep copy of CIMIsosurface.</p>


```csharp
public CIMIsosurface Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Gets or sets the isosurface color.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Reconstructs the CIMIsosurface with a specified state from a JSON encoding.</p>


```csharp
public static CIMIsosurface FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Gets or sets the ID.</p>


```csharp
public string ID { get; set; }
```
### IsCustomColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the color was set by user.</p>


```csharp
public bool IsCustomColor { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Gets or sets the isosurface name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMIsosurface and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Gets or sets the variable value.</p>


```csharp
public double Value { get; set; }
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the isosurface is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMIsosurface.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


