# CIMMultiSeriesChartProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Provides access to members that control multi series chart properties.</p>


## Object Signature

```csharp
public class CIMMultiSeriesChartProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultiSeriesChartProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Provides access to members that control multi series chart properties.</p>


```csharp
public CIMMultiSeriesChartProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMultiSeriesChartProperties.</p>


```csharp
public CIMMultiSeriesChartProperties Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether multi series chart properties are enabled.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMMultiSeriesChartProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMMultiSeriesChartProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMultiSeriesChartProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiSeriesChartProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


