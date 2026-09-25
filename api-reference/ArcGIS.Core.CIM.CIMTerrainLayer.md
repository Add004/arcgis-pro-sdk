# CIMTerrainLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Represents a terrain layer.</p>


## Object Signature

```csharp
public class CIMTerrainLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">A terrain layer draws a terrain dataset. A terrain dataset is a specialized data structure in the geodatabase that represents terrain surfaces based on vector measurements.</p>


## Members

### CIMTerrainLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Represents a terrain layer.</p>


```csharp
public CIMTerrainLayer()
```
### AnalysisToolsResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets the resolution use by analysis tools.</p>


```csharp
public double AnalysisToolsResolution { get; set; }
```
### AutoLOR

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not LOR should be updated when scale changes.</p>


```csharp
public bool AutoLOR { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTerrainLayer.</p>


```csharp
public CIMTerrainLayer Clone()
```
### CurrentResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets the current resolution.</p>


```csharp
public double CurrentResolution { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### DisplayField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets the display field.</p>


```csharp
public string DisplayField { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMTerrainLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTerrainLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### LockCurrentSurface

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the current surface should be updated based on scale change.</p>


```csharp
public bool LockCurrentSurface { get; set; }
```
### PointBudget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets the point budget.</p>


```csharp
public int PointBudget { get; set; }
```
### PyramidHonored

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the current surface resolution honors the scale/resolution relationship in the pyramid definition.</p>


```csharp
public bool PyramidHonored { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Renderers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets the renderers.</p>


```csharp
public CIMTinRenderer[] Renderers { get; set; }
```
### ScaleSymbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether symbols should be scaled.</p>


```csharp
public bool ScaleSymbols { get; set; }
```
### ShowResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the resolution should be shown in the contents pane.</p>


```csharp
public bool ShowResolution { get; set; }
```
### TargetResolution

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets the target resolution.</p>


```csharp
public double TargetResolution { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTerrainLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UseOverviewTerrain

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the terrain overview should be used.</p>


```csharp
public bool UseOverviewTerrain { get; set; }
```
### UsePointBudget

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the point budget should be used.</p>


```csharp
public bool UsePointBudget { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTerrainLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


