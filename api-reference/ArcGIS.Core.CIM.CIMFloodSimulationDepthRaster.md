# CIMFloodSimulationDepthRaster

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Provides access to properties of a depth raster for flood simulation.</p>


## Object Signature

```csharp
public class CIMFloodSimulationDepthRaster : CIMFloodSimulationObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFloodSimulationDepthRaster()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Provides access to properties of a depth raster for flood simulation.</p>


```csharp
public CIMFloodSimulationDepthRaster()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFloodSimulationDepthRaster.</p>


```csharp
public CIMFloodSimulationDepthRaster Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Reconstructs the CIMFloodSimulationDepthRaster with a specified state from a JSON encoding.</p>


```csharp
public static CIMFloodSimulationDepthRaster FromJson(string json, JsonDeserializationSettings settings = null)
```
### LinearUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Gets or sets the linear unit.</p>


```csharp
public LinearUnit LinearUnit { get; set; }
```
### RasterDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Gets or sets the data connection for the raster source.</p>


```csharp
public CIMDataConnection RasterDataConnection { get; set; }
```
### RasterIndex

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Gets or sets the raster index for multidimensional rasters.</p>


```csharp
public int RasterIndex { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFloodSimulationDepthRaster and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFloodSimulationDepthRaster.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


