# CIMTimelineSwimlane

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Represents a swimlane in a timeline.</p>


## Object Signature

```csharp
public class CIMTimelineSwimlane : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimelineSwimlane()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Represents a swimlane in a timeline.</p>


```csharp
public CIMTimelineSwimlane()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Gets or sets an alias for the swimlane.</p>


```csharp
public string Alias { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimelineSwimlane.</p>


```csharp
public CIMTimelineSwimlane Clone()
```
### DrawingInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Gets or sets the timeline swimlane drawing information.</p>


```csharp
public CIMTimelineLaneDrawingInfo DrawingInfo { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the swimlane is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Reconstructs the CIMTimelineSwimlane with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimelineSwimlane FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Gets or sets the Id of for the timeline swimlane.</p>


```csharp
public string ID { get; set; }
```
### Layers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Gets or sets the timeline layers.</p>


```csharp
public CIMTimelineLayer[] Layers { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SwimlaneExpanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the swimlane is expanded in the timeline.</p>


```csharp
public bool SwimlaneExpanded { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimelineSwimlane and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the swimlane is visible.</p>


```csharp
public bool Visibility { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimelineSwimlane.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


