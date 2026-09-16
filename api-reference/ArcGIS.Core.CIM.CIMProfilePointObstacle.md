# CIMProfilePointObstacle

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Defines the properties for a Point obstacle.</p>


## Object Signature

```csharp
public class CIMProfilePointObstacle : CIMProfileObstacle, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfilePointObstacle()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Defines the properties for a Point obstacle.</p>


```csharp
public CIMProfilePointObstacle()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfilePointObstacle.</p>


```csharp
public CIMProfilePointObstacle Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Reconstructs the CIMProfilePointObstacle with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfilePointObstacle FromJson(string json, JsonDeserializationSettings settings = null)
```
### MarkerLocation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the location of marker symbol for obstacle.</p>


```csharp
public ProfileObstacleMarkerLocation MarkerLocation { get; set; }
```
### ObstacleBaseSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the line symbol to connect from base of the grid to base of the obstacle.</p>


```csharp
public CIMSymbolReference ObstacleBaseSymbol { get; set; }
```
### ObstacleHeightSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the line symbol to display the height of the obstacle (base to top of obstacle).</p>


```csharp
public CIMSymbolReference ObstacleHeightSymbol { get; set; }
```
### ObstacleMarkerSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the point symbol displayed based in the marker location.</p>


```csharp
public CIMSymbolReference ObstacleMarkerSymbol { get; set; }
```
### ObstacleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the text symbol to display the number of obstacle at the marker location.</p>


```csharp
public CIMSymbolReference ObstacleTextSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowOnlyShadowingObstacles

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether only shadowing obstacles are displayed.</p>


```csharp
public bool ShowOnlyShadowingObstacles { get; set; }
```
### SubstituteObstacleBaseSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the substitute base symbol.</p>


```csharp
public CIMSymbolReference SubstituteObstacleBaseSymbol { get; set; }
```
### SubstituteObstacleHeightSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the substitute height symbol.</p>


```csharp
public CIMSymbolReference SubstituteObstacleHeightSymbol { get; set; }
```
### SubstituteObstacleMarkerSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the substitute marker symbol.</p>


```csharp
public CIMSymbolReference SubstituteObstacleMarkerSymbol { get; set; }
```
### SubstituteObstacleTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Gets or sets the substitute text symbol.</p>


```csharp
public CIMSymbolReference SubstituteObstacleTextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfilePointObstacle and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePointObstacle.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


