# CIMDataEngineeringPreviewChart

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Provide information of a preview chart.</p>


## Object Signature

```csharp
public class CIMDataEngineeringPreviewChart : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDataEngineeringPreviewChart()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Provide information of a preview chart.</p>


```csharp
public CIMDataEngineeringPreviewChart()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDataEngineeringPreviewChart.</p>


```csharp
public CIMDataEngineeringPreviewChart Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Reconstructs the CIMDataEngineeringPreviewChart with a specified state from a JSON encoding.</p>


```csharp
public static CIMDataEngineeringPreviewChart FromJson(string json, JsonDeserializationSettings settings = null)
```
### Maximum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Gets or sets maximum/last in the X axis.</p>


```csharp
public object Maximum { get; set; }
```
### Minimum

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Gets or sets minimum/first in the X axis.</p>


```csharp
public object Minimum { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDataEngineeringPreviewChart and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Gets or sets preview chart values.</p>


```csharp
public object[] Values { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDataEngineeringPreviewChart.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


