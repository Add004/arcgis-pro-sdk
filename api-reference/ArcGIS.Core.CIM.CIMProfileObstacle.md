# CIMProfileObstacle

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Represents common properties for all the obstacles.</p>


## Object Signature

```csharp
public class CIMProfileObstacle : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfileObstacle()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Represents common properties for all the obstacles.</p>


```csharp
public CIMProfileObstacle()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfileObstacle.</p>


```csharp
public CIMProfileObstacle Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Reconstructs the CIMProfileObstacle with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfileObstacle FromJson(string json, JsonDeserializationSettings settings = null)
```
### ObstacleLayerName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Gets or sets the name connecting display options to obstacle layers coming from Obstacle JSON (read only).</p>


```csharp
public string ObstacleLayerName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowPenetrating

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to the obstacle only if it penetrates OIS Surface.</p>


```csharp
public bool ShowPenetrating { get; set; }
```
### SymbolSubstitutionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Gets or sets the type of substitution applied to the obstacle symbol.</p>


```csharp
public ProfileObstacleSymbolSubstitutionType SymbolSubstitutionType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfileObstacle and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileObstacle.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


