# CIMProfileTerrainDisplay

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Settings to control how the terrain information is being displayed in the profile.</p>


## Object Signature

```csharp
public class CIMProfileTerrainDisplay : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfileTerrainDisplay()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Settings to control how the terrain information is being displayed in the profile.</p>


```csharp
public CIMProfileTerrainDisplay()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfileTerrainDisplay.</p>


```csharp
public CIMProfileTerrainDisplay Clone()
```
### DisplayOption

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Gets or sets the display option for terrain.</p>


```csharp
public ProfileTerrainDisplayOption DisplayOption { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Reconstructs the CIMProfileTerrainDisplay with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfileTerrainDisplay FromJson(string json, JsonDeserializationSettings settings = null)
```
### PenetratingTerrainSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Gets or sets the display Symbol for the penetrating terrain or terrain above OIS surface.</p>


```csharp
public CIMSymbolReference PenetratingTerrainSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TerrainSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Gets or sets the display Symbol for the entire terrain or terrain below OIS surface.</p>


```csharp
public CIMSymbolReference TerrainSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfileTerrainDisplay and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileTerrainDisplay.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


