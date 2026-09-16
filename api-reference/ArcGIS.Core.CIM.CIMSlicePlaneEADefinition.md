# CIMSlicePlaneEADefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Represents a slice plane exploratory analysis definition.</p>


## Object Signature

```csharp
public class CIMSlicePlaneEADefinition : CIMExploratoryAnalysisDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSlicePlaneEADefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Represents a slice plane exploratory analysis definition.</p>


```csharp
public CIMSlicePlaneEADefinition()
```
### CenterPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Gets or sets the observer position.</p>


```csharp
public MapPoint CenterPoint { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSlicePlaneEADefinition.</p>


```csharp
public CIMSlicePlaneEADefinition Clone()
```
### CullDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Gets or sets the direction that is clipped.</p>


```csharp
public CullDirection CullDirection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMSlicePlaneEADefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMSlicePlaneEADefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Gets or sets the heading in degrees from North. 0 is North, 90 is West, 180 is South, -90 is East, etc.</p>


```csharp
public double Heading { get; set; }
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Gets or sets the height.</p>


```csharp
public double Height { get; set; }
```
### Pitch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Gets or sets the pitch in degrees from horizontal. 0 is horizontal, 90 is looking directly up and -90 is looking directly down.</p>


```csharp
public double Pitch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSlicePlaneEADefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Gets or sets the width.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSlicePlaneEADefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


