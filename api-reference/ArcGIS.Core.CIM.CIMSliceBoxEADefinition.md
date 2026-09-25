# CIMSliceBoxEADefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Represents a slice box exploratory analysis definition.</p>


## Object Signature

```csharp
public class CIMSliceBoxEADefinition : CIMExploratoryAnalysisDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSliceBoxEADefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Represents a slice box exploratory analysis definition.</p>


```csharp
public CIMSliceBoxEADefinition()
```
### CenterPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Gets or sets the center position.</p>


```csharp
public MapPoint CenterPoint { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSliceBoxEADefinition.</p>


```csharp
public CIMSliceBoxEADefinition Clone()
```
### CullDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Gets or sets the depth.</p>


```csharp
public CullDirection CullDirection { get; set; }
```
### Depth

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Gets or sets the depth.</p>


```csharp
public double Depth { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMSliceBoxEADefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMSliceBoxEADefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Gets or sets the heading in degrees from North. 0 is North, 90 is West, 180 is South, -90 is East, etc.</p>


```csharp
public double Heading { get; set; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Gets or sets the height.</p>


```csharp
public double Height { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSliceBoxEADefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Gets or sets the width.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceBoxEADefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


