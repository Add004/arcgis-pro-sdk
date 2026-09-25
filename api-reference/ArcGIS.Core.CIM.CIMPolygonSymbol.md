# CIMPolygonSymbol

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Represents a polygon symbol which is used to draw polygon features or polygon graphics.</p>


## Object Signature

```csharp
public class CIMPolygonSymbol : CIMMultiLayerSymbol, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPolygonSymbol()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Represents a polygon symbol which is used to draw polygon features or polygon graphics.</p>


```csharp
public CIMPolygonSymbol()
```
### AngleAlignment

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Gets or sets whether polygon symbol fills align to the map or to the display when a rotation is applied to the map.</p>


```csharp
public AngleAlignment AngleAlignment { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPolygonSymbol.</p>


```csharp
public CIMPolygonSymbol Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Reconstructs the CIMPolygonSymbol with a specified state from a JSON encoding.</p>


```csharp
public static CIMPolygonSymbol FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPolygonSymbol and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPolygonSymbol.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


