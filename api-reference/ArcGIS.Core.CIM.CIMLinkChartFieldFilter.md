# CIMLinkChartFieldFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Represents additional settings used by a Link chart field filter.</p>


## Object Signature

```csharp
public class CIMLinkChartFieldFilter : CIMLinkChartFilter, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartFieldFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Represents additional settings used by a Link chart field filter.</p>


```csharp
public CIMLinkChartFieldFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartFieldFilter.</p>


```csharp
public CIMLinkChartFieldFilter Clone()
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Gets or sets the field that is used to filter the link chart entity or relationship.</p>


```csharp
public string Field { get; set; }
```
### FieldType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Gets or sets the field type that is used to filter the link chart entity or relationship.</p>


```csharp
public esriFieldType FieldType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartFieldFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartFieldFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartFieldFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFieldFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


