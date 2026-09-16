# CIMProfileRunway

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Display properties for Runway.</p>


## Object Signature

```csharp
public class CIMProfileRunway : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProfileRunway()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Display properties for Runway.</p>


```csharp
public CIMProfileRunway()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProfileRunway.</p>


```csharp
public CIMProfileRunway Clone()
```
### ElevationChangeThreshold

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Gets or sets the percentage change between two elevation values when we can show
the text symbol. Range is calculated by maximum and minimum elevation
of the runway.</p>


```csharp
public double ElevationChangeThreshold { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Reconstructs the CIMProfileRunway with a specified state from a JSON encoding.</p>


```csharp
public static CIMProfileRunway FromJson(string json, JsonDeserializationSettings settings = null)
```
### Precision

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Gets or sets the number of decimal places for runway elevation.</p>


```csharp
public int Precision { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RunwayLineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Gets or sets the display symbol for runway.</p>


```csharp
public CIMSymbolReference RunwayLineSymbol { get; set; }
```
### RunwayTextSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Gets or sets the text symbol for runway elevation.</p>


```csharp
public CIMSymbolReference RunwayTextSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProfileRunway and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProfileRunway.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


