# CIMProfilePolyObstacle

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Represents a profile poly obstacle.</p>


## Object Signature

```csharp
public class CIMProfilePolyObstacle : CIMProfileObstacle, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfilePolyObstacle()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Represents a profile poly obstacle.</p>


```csharp
public CIMProfilePolyObstacle()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfilePolyObstacle.</p>


```csharp
public CIMProfilePolyObstacle Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Reconstructs the CIMProfilePolyObstacle with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfilePolyObstacle FromJson(string json, JsonDeserializationSettings settings = null)
```
### GroundDisplayOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Gets or sets the option to display how the base of obstacle is shown.</p>


```csharp
public ProfileObstacleGroundDisplayOption GroundDisplayOption { get; set; }
```
### ObstacleSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Gets or sets the symbol used to draw the obstacle.</p>


```csharp
public CIMSymbolReference ObstacleSymbol { get; set; }
```
### PolygonPolylineGroundDisplayOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Gets or sets the option to display how the base of obstacle is shown.</p>


```csharp
public ProfilePolyObstacleDisplayOption PolygonPolylineGroundDisplayOption { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubstituteObstacleSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Gets or sets the substitute obstacle symbol.</p>


```csharp
public CIMSymbolReference SubstituteObstacleSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfilePolyObstacle and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfilePolyObstacle.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


