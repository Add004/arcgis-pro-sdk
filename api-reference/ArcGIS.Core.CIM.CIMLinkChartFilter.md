# CIMLinkChartFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Represents the link chart filter information.</p>


## Object Signature

```csharp
public class CIMLinkChartFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Represents the link chart filter information.</p>


```csharp
public CIMLinkChartFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartFilter.</p>


```csharp
public CIMLinkChartFilter Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the description of the link chart filter.</p>


```csharp
public string Description { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the link chart filter is enabled or not.</p>


```csharp
public bool Enabled { get; set; }
```
### FilterScope

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the value that indicates what link chart component is filtered: entities, relationships, or both.</p>


```csharp
public LinkChartFilterScope FilterScope { get; set; }
```
### FilterStage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the value that indicates when the link chart filter is applied.</p>


```csharp
public LinkChartFilterStage FilterStage { get; set; }
```
### FilterType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the filter type of the link chart filter.</p>


```csharp
public LinkChartFilterType FilterType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the ID of the link chart filter.</p>


```csharp
public string ID { get; set; }
```
### IsExclusion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is an exclusion filter.</p>


```csharp
public bool IsExclusion { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the name of the link chart filter.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TargetIds

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the entity and or relationship Ids to filter.</p>


```csharp
public string[] TargetIds { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ValueSetURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Gets or sets the binary reference of the filter values for the link chart filter.</p>


```csharp
public string ValueSetURI { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


