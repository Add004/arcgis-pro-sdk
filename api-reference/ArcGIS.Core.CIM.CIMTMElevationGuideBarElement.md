# CIMTMElevationGuideBarElement

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Represents TM Elevation Guide Bar surround element.</p>


## Object Signature

```csharp
public class CIMTMElevationGuideBarElement : CIMMapProductSurround, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTMElevationGuideBarElement()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Represents TM Elevation Guide Bar surround element.</p>


```csharp
public CIMTMElevationGuideBarElement()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTMElevationGuideBarElement.</p>


```csharp
public CIMTMElevationGuideBarElement Clone()
```
### ElevationBandLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets elevation bands feature class, the number of
bands in the bar is dependent on the number of bands identified
in feature class.</p>


```csharp
public string ElevationBandLayerURI { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Reconstructs the CIMTMElevationGuideBarElement with a specified state from a JSON encoding.</p>


```csharp
public static CIMTMElevationGuideBarElement FromJson(string json, JsonDeserializationSettings settings = null)
```
### HighBandSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets the high band symbol in the elevation guide bar.</p>


```csharp
public CIMSymbolReference HighBandSymbol { get; set; }
```
### HighestBandSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets the highest band symbol in the elevation guide bar.</p>


```csharp
public CIMSymbolReference HighestBandSymbol { get; set; }
```
### LineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets the symbol used for line elements in the elevation guide bar.</p>


```csharp
public CIMSymbolReference LineSymbol { get; set; }
```
### LowBandSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets the low band symbol in the elevation guide bar.</p>


```csharp
public CIMSymbolReference LowBandSymbol { get; set; }
```
### MediumBandSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets the medium band symbol in the elevation guide bar.</p>


```csharp
public CIMSymbolReference MediumBandSymbol { get; set; }
```
### NumberOfBands

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets the number of bands displayed in the Elevation Guide Bar,
if data is from source that does not have Bands field.</p>


```csharp
public int NumberOfBands { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Gets or sets the symbol used for text elements in the elevation guide bar.</p>


```csharp
public CIMSymbolReference TextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTMElevationGuideBarElement and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTMElevationGuideBarElement.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


