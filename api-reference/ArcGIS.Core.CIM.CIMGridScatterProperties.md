# CIMGridScatterProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Provides access to members that control the display of grid scatter plots.</p>


## Object Signature

```csharp
public class CIMGridScatterProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGridScatterProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Provides access to members that control the display of grid scatter plots.</p>


```csharp
public CIMGridScatterProperties()
```
### BreakColors

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Gets or sets the color for each break in the grid scatter plots.</p>


```csharp
public CIMColor[] BreakColors { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGridScatterProperties.</p>


```csharp
public CIMGridScatterProperties Clone()
```
### ColorRamp

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Gets or sets the color ramp for the grid scatter plots when RSquared or Pearson's R is selected.</p>


```csharp
public CIMColorRamp ColorRamp { get; set; }
```
### DisplayOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Gets or sets the display option for the grid scatter plots.</p>


```csharp
public ChartScatterDisplayOption DisplayOption { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMGridScatterProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMGridScatterProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### RSquareText

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Gets or sets the text symbol properties for the RSquare.</p>


```csharp
public CIMChartTextProperties RSquareText { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowPValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show p-value in the chart.</p>


```csharp
public bool ShowPValue { get; set; }
```
### SortByType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Gets or sets the sort by type.</p>


```csharp
public ChartSPMSortByType SortByType { get; set; }
```
### SortDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Gets or sets the direction type of sort order.</p>


```csharp
public ChartSortDirection SortDirection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGridScatterProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridScatterProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


