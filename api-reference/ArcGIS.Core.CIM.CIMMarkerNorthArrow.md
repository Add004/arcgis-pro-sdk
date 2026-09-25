# CIMMarkerNorthArrow

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Represents a marker north arrow on a page layout.</p>


## Object Signature

```csharp
public class CIMMarkerNorthArrow : CIMNorthArrow, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMarkerNorthArrow()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Represents a marker north arrow on a page layout.</p>


```csharp
public CIMMarkerNorthArrow()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMarkerNorthArrow.</p>


```csharp
public CIMMarkerNorthArrow Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Reconstructs the CIMMarkerNorthArrow with a specified state from a JSON encoding.</p>


```csharp
public static CIMMarkerNorthArrow FromJson(string json, JsonDeserializationSettings settings = null)
```
### NorthType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the type of north arrow.</p>


```csharp
public NorthType NorthType { get; set; }
```
### PointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Gets or sets the point symbol for a north arrow.</p>


```csharp
public CIMSymbolReference PointSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMarkerNorthArrow and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMarkerNorthArrow.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


