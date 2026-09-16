# CIMProfileTerrain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Display properties for Terrain.</p>


## Object Signature

```csharp
public class CIMProfileTerrain : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfileTerrain()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Display properties for Terrain.</p>


```csharp
public CIMProfileTerrain()
```
### CenterLineTerrain

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Gets or sets the display settings for  CenterLine elevation of terrain.</p>


```csharp
public CIMProfileTerrainDisplay CenterLineTerrain { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfileTerrain.</p>


```csharp
public CIMProfileTerrain Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Reconstructs the CIMProfileTerrain with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfileTerrain FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxTerrain

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Gets or sets the display settings for maximum elevation of terrain.</p>


```csharp
public CIMProfileTerrainDisplay MaxTerrain { get; set; }
```
### MinTerrain

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Gets or sets the display settings for minimum elevation of terrain.</p>


```csharp
public CIMProfileTerrainDisplay MinTerrain { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowOutline

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show only the outline of terrain.</p>


```csharp
public bool ShowOutline { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfileTerrain and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrain.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


