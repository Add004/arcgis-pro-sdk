# CIMGridLine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Represents latitudes or longitudes for a graticule.
Represents eastings or nothings for a grid.</p>


## Object Signature

```csharp
public class CIMGridLine : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGridLine()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Represents latitudes or longitudes for a graticule.
Represents eastings or nothings for a grid.</p>


```csharp
public CIMGridLine()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGridLine.</p>


```csharp
public CIMGridLine Clone()
```
### ElementType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets the type of the graticule element.</p>


```csharp
public GridElementType ElementType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Reconstructs the CIMGridLine with a specified state from a JSON encoding.</p>


```csharp
public static CIMGridLine FromJson(string json, JsonDeserializationSettings settings = null)
```
### FromTick

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets the properties of the tick that is at the start of the grid line it represents.</p>


```csharp
public CIMExteriorTick FromTick { get; set; }
```
### GridLineOrientation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets the orientation of the gridLine with reference to the coordinate system of the spatial reference. For graticules it is latitudes and longitudes. For grids it is eastings and northings.</p>


```csharp
public GridLineOrientation GridLineOrientation { get; set; }
```
### InteriorTicks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets the properties of the interior ticks for a grid line.</p>


```csharp
public CIMInteriorTick[] InteriorTicks { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets name of the grid line.</p>


```csharp
public string Name { get; set; }
```
### Pattern

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets the pattern of the grid lines.</p>


```csharp
public CIMGridPattern Pattern { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets symbol of the grid line.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGridLine and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToTick

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets the properties of the tick that is at the end of the grid line it represents.</p>


```csharp
public CIMExteriorTick ToTick { get; set; }
```
### VisibleIndices

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Gets or sets the visibility of the corner labels to edges by index.</p>


```csharp
public int[] VisibleIndices { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGridLine.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


