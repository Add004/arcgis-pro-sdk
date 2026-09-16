# CIMTopoCompassRose

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Represents a compass rose north arrow which displays declination with a compass dial.</p>


## Object Signature

```csharp
public class CIMTopoCompassRose : CIMTopoNorthArrow, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTopoCompassRose()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Represents a compass rose north arrow which displays declination with a compass dial.</p>


```csharp
public CIMTopoCompassRose()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTopoCompassRose.</p>


```csharp
public CIMTopoCompassRose Clone()
```
### DegreeLabelFrequency

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Gets or sets the frequency in which a degree label is displayed. Valid values are 0 to 359.</p>


```csharp
public int DegreeLabelFrequency { get; set; }
```
### DegreeMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Gets or sets the line symbol used to draw the degree marks on compass dial.</p>


```csharp
public CIMSymbolReference DegreeMarkSymbol { get; set; }
```
### DivisionMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Gets or sets the line symbol used to draw the division marks on compass dial.</p>


```csharp
public CIMSymbolReference DivisionMarkSymbol { get; set; }
```
### Divisions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Gets or sets the frequency of divisions on the compass dial. Valid values are 0 to 359.</p>


```csharp
public int Divisions { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Reconstructs the CIMTopoCompassRose with a specified state from a JSON encoding.</p>


```csharp
public static CIMTopoCompassRose FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SubdivisionMarkSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Gets or sets the line symbol used to draw the sub division marks on compass dial.</p>


```csharp
public CIMSymbolReference SubdivisionMarkSymbol { get; set; }
```
### Subdivisions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Gets or sets the frequency of subdivisions on the compass dial. Valid values are 0 to 359.</p>


```csharp
public int Subdivisions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTopoCompassRose and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTopoCompassRose.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


