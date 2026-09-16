# CIMGridChartProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Provides access to members that control grid chart properties.</p>


## Object Signature

```csharp
public class CIMGridChartProperties : CIMMultiSeriesChartProperties, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGridChartProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Provides access to members that control grid chart properties.</p>


```csharp
public CIMGridChartProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGridChartProperties.</p>


```csharp
public CIMGridChartProperties Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMGridChartProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMGridChartProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### MiniChartOutlineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties of the outline for the non-selected mini chart.</p>


```csharp
public CIMChartLineSymbolProperties MiniChartOutlineSymbolProperties { get; set; }
```
### MiniChartTitleText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets the text symbol properties of the series title for the mini chart.</p>


```csharp
public CIMChartTextProperties MiniChartTitleText { get; set; }
```
### MiniChartsPerRow

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets the number of mini charts per row of a grid chart.</p>


```csharp
public int MiniChartsPerRow { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ScatterProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets the properties for the grid scatter plots.</p>


```csharp
public CIMGridScatterProperties ScatterProperties { get; set; }
```
### SelectedMiniChart

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets the index of the selected mini chart.</p>


```csharp
public int SelectedMiniChart { get; set; }
```
### SelectionLineSymbolProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets the line symbol properties of the outline for the selected mini chart.</p>


```csharp
public CIMChartLineSymbolProperties SelectionLineSymbolProperties { get; set; }
```
### ShowPreviewChart

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show a zoomed-in preview chart.</p>


```csharp
public bool ShowPreviewChart { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGridChartProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseSeriesMinMaxForAxisX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether each mini chart will use corresponding series' minimum and maximum of x values for axis X.
If false it will use the combined series' minimum and maximum.</p>


```csharp
public bool UseSeriesMinMaxForAxisX { get; set; }
```
### UseSeriesMinMaxForAxisY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether each mini chart will use corresponding series' minimum and maximum of y values for axis Y.
If false it will use the combined series' minimum and maximum.</p>


```csharp
public bool UseSeriesMinMaxForAxisY { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridChartProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


