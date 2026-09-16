# CIMRasterLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Represents a raster layer which displays raster imagery stored in a raster dataset.</p>


## Object Signature

```csharp
public class CIMRasterLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRasterLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Represents a raster layer which displays raster imagery stored in a raster dataset.</p>


```csharp
public CIMRasterLayer()
```
### ActiveCustomColorizer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the active custom colorizer.</p>


```csharp
public string ActiveCustomColorizer { get; set; }
```
### ActiveRangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the name of the active range.</p>


```csharp
public string ActiveRangeName { get; set; }
```
### ActiveSlice

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets a multidimensional display definition describing the current display slice.</p>


```csharp
public CIMRasterMultidimensionalDisplayDefinition ActiveSlice { get; set; }
```
### ActiveVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the active variables.</p>


```csharp
public string[] ActiveVariables { get; set; }
```
### AttributeTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the raster table definition.</p>


```csharp
public CIMRasterTable AttributeTable { get; set; }
```
### AutoComputeStatsHistogram

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to automatically compute the statistics histogram.</p>


```csharp
public bool AutoComputeStatsHistogram { get; set; }
```
### AuxiliaryRasterProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the auxiliary raster properties.</p>


```csharp
public CIMAuxiliaryRasterProperties AuxiliaryRasterProperties { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRasterLayer.</p>


```csharp
public CIMRasterLayer Clone()
```
### Colorizer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the raster colorizer.</p>


```csharp
public CIMRasterColorizer Colorizer { get; set; }
```
### CustomColorizers

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the custom colorizers.</p>


```csharp
public CIMRasterColorizer[] CustomColorizers { get; set; }
```
### DataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection for the raster this layer is based on.</p>


```csharp
public CIMDataConnection DataConnection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMRasterLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMRasterLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### MultidimensionalExtent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets a multidimensional extent definition describing the data cube(s) used for analysis.</p>


```csharp
public CIMRasterMultidimensionalExtentDefinition MultidimensionalExtent { get; set; }
```
### RangeDefinitions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the range definitions.</p>


```csharp
public CIMRangeDefinition[] RangeDefinitions { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RenderingRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the rendering rule.</p>


```csharp
public CIMRenderingRule RenderingRule { get; set; }
```
### TimeDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the time definition.</p>


```csharp
public CIMTimeDataDefinition TimeDefinition { get; set; }
```
### TimeDimensionFields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the time dimension fields.</p>


```csharp
public CIMTimeDimensionDefinition TimeDimensionFields { get; set; }
```
### TimeDisplayDefinition

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Gets or sets the time display definition.</p>


```csharp
public CIMTimeDisplayDefinition TimeDisplayDefinition { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRasterLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRasterLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


