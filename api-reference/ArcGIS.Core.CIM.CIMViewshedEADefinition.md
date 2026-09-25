# CIMViewshedEADefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Represents a viewshed exploratory analysis definition.</p>


## Object Signature

```csharp
public class CIMViewshedEADefinition : CIMExploratoryAnalysisDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMViewshedEADefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Represents a viewshed exploratory analysis definition.</p>


```csharp
public CIMViewshedEADefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMViewshedEADefinition.</p>


```csharp
public CIMViewshedEADefinition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMViewshedEADefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMViewshedEADefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Heading

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Gets or sets the heading in degrees from North. 0 is North, 90 is West, 180 is South, -90 is East, etc.</p>


```csharp
public double Heading { get; set; }
```
### HorizontalAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Gets or sets the horizontal viewing angle.</p>


```csharp
public double HorizontalAngle { get; set; }
```
### MaximumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Gets or sets the maximum distance to be analyzed.</p>


```csharp
public double MaximumDistance { get; set; }
```
### MinimumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Gets or sets the minimum distance to be analyzed.</p>


```csharp
public double MinimumDistance { get; set; }
```
### Observer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Gets or sets the observer position.</p>


```csharp
public MapPoint Observer { get; set; }
```
### Pitch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Gets or sets the pitch in degrees from horizontal. 0 is horizontal, 90 is looking directly up and -90 is looking directly down.</p>


```csharp
public double Pitch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMViewshedEADefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Gets or sets the vertical viewing angle.</p>


```csharp
public double VerticalAngle { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewshedEADefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


