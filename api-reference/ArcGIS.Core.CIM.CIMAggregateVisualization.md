# CIMAggregateVisualization

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Describes the appearance of aggregated features.</p>


## Object Signature

```csharp
public class CIMAggregateVisualization : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAggregateVisualization()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Describes the appearance of aggregated features.</p>


```csharp
public CIMAggregateVisualization()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAggregateVisualization.</p>


```csharp
public CIMAggregateVisualization Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Reconstructs the CIMAggregateVisualization with a specified state from a JSON encoding.</p>


```csharp
public static CIMAggregateVisualization FromJson(string json, JsonDeserializationSettings settings = null)
```
### LabelClass

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Gets or sets the label class used by the aggregated features.</p>


```csharp
public CIMLabelClass LabelClass { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Gets or sets the renderer used by the aggregated features.</p>


```csharp
public CIMRenderer Renderer { get; set; }
```
### ShowLabels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to show labels for the aggregated features.</p>


```csharp
public bool ShowLabels { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAggregateVisualization and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregateVisualization.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


