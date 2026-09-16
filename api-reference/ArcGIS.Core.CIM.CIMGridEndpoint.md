# CIMGridEndpoint

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Represents an end point of a component. For ex: The labels for ticks are
defined using an endPoint object.</p>


## Object Signature

```csharp
public class CIMGridEndpoint : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGridEndpoint()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Represents an end point of a component. For ex: The labels for ticks are
defined using an endPoint object.</p>


```csharp
public CIMGridEndpoint()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGridEndpoint.</p>


```csharp
public CIMGridEndpoint Clone()
```
### DrawCornerLabelsInside

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw corner labels inside the map grid edges.</p>


```csharp
public bool DrawCornerLabelsInside { get; set; }
```
### DrawLabelsParallel

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to draw the labels parallel to the map grid edges.</p>


```csharp
public bool DrawLabelsParallel { get; set; }
```
### EdgeVisibilityFilter

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Gets or sets a value indicating which labels to draw along the map grid edges.</p>


```csharp
public EndPointSelection EdgeVisibilityFilter { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Reconstructs the CIMGridEndpoint with a specified state from a JSON encoding.</p>


```csharp
public static CIMGridEndpoint FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridLabelTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Gets or sets the grid label template for each endpoint.</p>


```csharp
public CIMGridLabelTemplate GridLabelTemplate { get; set; }
```
### LineSelection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Gets or sets the end point selection.</p>


```csharp
public int LineSelection { get; set; }
```
### Offset

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Gets or sets the offset of the labels.</p>


```csharp
public double Offset { get; set; }
```
### Position

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Gets or sets the position of the labels of the end points.</p>


```csharp
public int Position { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGridEndpoint and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridEndpoint.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


