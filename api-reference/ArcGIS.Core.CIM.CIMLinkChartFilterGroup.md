# CIMLinkChartFilterGroup

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Represents a group of link chart filters.</p>


## Object Signature

```csharp
public class CIMLinkChartFilterGroup : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLinkChartFilterGroup()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Represents a group of link chart filters.</p>


```csharp
public CIMLinkChartFilterGroup()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLinkChartFilterGroup.</p>


```csharp
public CIMLinkChartFilterGroup Clone()
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Gets or sets the description of the link chart filter group.</p>


```csharp
public string Description { get; set; }
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the link chart filter group is enabled or not.</p>


```csharp
public bool Enabled { get; set; }
```
### Filters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Gets or sets the link chart filters in the group.</p>


```csharp
public CIMLinkChartFilter[] Filters { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Reconstructs the CIMLinkChartFilterGroup with a specified state from a JSON encoding.</p>


```csharp
public static CIMLinkChartFilterGroup FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Gets or sets the ID of the link chart filter group.</p>


```csharp
public string ID { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Gets or sets the name of the link chart filter group.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLinkChartFilterGroup and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLinkChartFilterGroup.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


