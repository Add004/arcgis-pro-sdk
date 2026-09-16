# CIMWaterFill

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Represents a water fill which fills polygonal geometry with animated water.</p>


## Object Signature

```csharp
public class CIMWaterFill : CIMFill, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMWaterFill()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Represents a water fill which fills polygonal geometry with animated water.</p>


```csharp
public CIMWaterFill()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Creates a deep copy of CIMWaterFill.</p>


```csharp
public CIMWaterFill Clone()
```
### Color

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Gets or sets the intrinsic color of the water.</p>


```csharp
public CIMColor Color { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Reconstructs the CIMWaterFill with a specified state from a JSON encoding.</p>


```csharp
public static CIMWaterFill FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMWaterFill and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WaterbodySize

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Gets or sets the waterbody size allowing for a range of sizes from small pools to oceans. This property along with wave strength are the parameters which drive the wave appearance.</p>


```csharp
public WaterbodySize WaterbodySize { get; set; }
```
### WaveDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Gets or sets the azimuthal bearing for direction of the waves. Only has effect when WasHasDirection is true.</p>


```csharp
public double WaveDirection { get; set; }
```
### WaveHasDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the waves are directionless (false), or if they have a dominant direction (true).</p>


```csharp
public bool WaveHasDirection { get; set; }
```
### WaveStrength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Gets or sets the strength of the waves. This property along with waterbody size are the parameters which drive the wave appearance.</p>


```csharp
public WaveStrength WaveStrength { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWaterFill.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


