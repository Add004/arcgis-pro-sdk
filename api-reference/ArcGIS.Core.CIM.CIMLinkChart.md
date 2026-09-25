# CIMLinkChart

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Represents a link chart.</p>


## Object Signature

```csharp
public class CIMLinkChart : CIMLinkChartBase, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChart()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Represents a link chart.</p>


```csharp
public CIMLinkChart()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChart.</p>


```csharp
public CIMLinkChart Clone()
```
### Entities

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets the link chart entities.</p>


```csharp
public CIMLinkChartEntity[] Entities { get; set; }
```
### Expanded

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this link chart is expanded in the contents pane.</p>


```csharp
public bool Expanded { get; set; }
```
### FilterByMinLinks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this link chart is filtered by the minimum number of links.</p>


```csharp
public bool FilterByMinLinks { get; set; }
```
### FilterGroups

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets the link chart filter groups.</p>


```csharp
public CIMLinkChartFilterGroup[] FilterGroups { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChart with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChart FromJson(string json, JsonDeserializationSettings settings = null)
```
### GraphMLURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets the URI of the binary reference containing the GraphML.</p>


```csharp
public string GraphMLURI { get; set; }
```
### InteractiveLayoutMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this link chart layout updates when the user moves nodes or links.</p>


```csharp
public bool InteractiveLayoutMode { get; set; }
```
### Layout

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets the link chart layout algorithm.</p>


```csharp
public LinkChartLayoutAlgorithm Layout { get; set; }
```
### Locked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this link chart is locked.</p>


```csharp
public bool Locked { get; set; }
```
### MinLinks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets the minimum number of links allowed in the filter.</p>


```csharp
public int MinLinks { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Relationships

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets the link chart relationships.</p>


```csharp
public CIMLinkChartRelationship[] Relationships { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChart and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Viewport

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Gets or sets the link chart viewport.</p>


```csharp
public CIMLinkChartViewport Viewport { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChart.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


