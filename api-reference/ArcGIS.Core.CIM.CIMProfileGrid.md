# CIMProfileGrid

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Grid shown for the profile.</p>


## Object Signature

```csharp
public class CIMProfileGrid : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfileGrid()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Grid shown for the profile.</p>


```csharp
public CIMProfileGrid()
```
### AutoGridExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to calculate the start and stop of grid automatically
If set to false user will set the minimum and maximum based on requirements.</p>


```csharp
public bool AutoGridExtent { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfileGrid.</p>


```csharp
public CIMProfileGrid Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Reconstructs the CIMProfileGrid with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfileGrid FromJson(string json, JsonDeserializationSettings settings = null)
```
### GridSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the line Symbol for the major grid lines.</p>


```csharp
public CIMSymbolReference GridSymbol { get; set; }
```
### HorizontalScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the horizontal scale for the profile.</p>


```csharp
public double HorizontalScale { get; set; }
```
### HorizontalScaleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the horizontal scale.</p>


```csharp
public CIMSymbolReference HorizontalScaleTextSymbol { get; set; }
```
### HorizontalScaleUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the horizontal scale units for the profile.</p>


```csharp
public LinearUnit HorizontalScaleUnits { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RunwayObstacleDisplay

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display obstacle along the runway.</p>


```csharp
public bool RunwayObstacleDisplay { get; set; }
```
### ShowAbsoluteHorizontalScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to display absolute or relative grid text automatically.</p>


```csharp
public bool ShowAbsoluteHorizontalScale { get; set; }
```
### ShowEntireApproach

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show the entire length of curved approach, or just show up to a particular distance.</p>


```csharp
public bool ShowEntireApproach { get; set; }
```
### SubDivisionSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the line symbol for the subdivision.</p>


```csharp
public CIMSymbolReference SubDivisionSymbol { get; set; }
```
### SubDivisionsX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the number of subdivisions in horizontal direction.</p>


```csharp
public int SubDivisionsX { get; set; }
```
### SubDivisionsY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the number of divisions in vertical direction.</p>


```csharp
public int SubDivisionsY { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfileGrid and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VerticalIntervalInFeet

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the vertical interval for scale in feet.</p>


```csharp
public int VerticalIntervalInFeet { get; set; }
```
### VerticalIntervalInMeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the vertical interval for scale in meters.</p>


```csharp
public int VerticalIntervalInMeters { get; set; }
```
### VerticalScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the vertical scale for the profile.</p>


```csharp
public double VerticalScale { get; set; }
```
### VerticalScaleLeftTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the vertical scale left.</p>


```csharp
public CIMSymbolReference VerticalScaleLeftTextSymbol { get; set; }
```
### VerticalScaleRightTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the text symbol for the vertical scale right.</p>


```csharp
public CIMSymbolReference VerticalScaleRightTextSymbol { get; set; }
```
### VerticalScaleUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the vertical scale units for the profile.</p>


```csharp
public LinearUnit VerticalScaleUnits { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the horizontal length maximum value.</p>


```csharp
public double XMax { get; set; }
```
### YMax

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the vertical scale maximum value.</p>


```csharp
public double YMax { get; set; }
```
### YMin

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileGrid.yml" sourcestartlinenumber="1">Gets or sets the vertical scale minimum value.</p>


```csharp
public double YMin { get; set; }
```


