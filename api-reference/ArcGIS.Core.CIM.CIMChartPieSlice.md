# CIMChartPieSlice

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Represents a slice in the pie chart.</p>


## Object Signature

```csharp
public class CIMChartPieSlice : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartPieSlice()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Represents a slice in the pie chart.</p>


```csharp
public CIMChartPieSlice()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartPieSlice.</p>


```csharp
public CIMChartPieSlice Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Reconstructs the CIMChartPieSlice with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartPieSlice FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Gets or sets the label for the slice.</p>


```csharp
public string Label { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Gets or sets the symbol for the slice.</p>


```csharp
public CIMChartFillSymbolProperties Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartPieSlice and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Gets or sets the value for the slice.</p>


```csharp
public string Value { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartPieSlice.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


