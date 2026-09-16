# CIMSunnyWeatherEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Represents a sunny weather effect to be applied to a scene.</p>


## Object Signature

```csharp
public class CIMSunnyWeatherEffect : CIMWeatherEffect, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSunnyWeatherEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Represents a sunny weather effect to be applied to a scene.</p>


```csharp
public CIMSunnyWeatherEffect()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSunnyWeatherEffect.</p>


```csharp
public CIMSunnyWeatherEffect Clone()
```
### CloudBaseElevation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Gets or sets the base cloud elevation in meters above sea level.</p>


```csharp
public int CloudBaseElevation { get; set; }
```
### CloudCover

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Gets or sets the percentage (0-1) of cloud cover in the sky.</p>


```csharp
public double CloudCover { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Reconstructs the CIMSunnyWeatherEffect with a specified state from a JSON encoding.</p>


```csharp
public static CIMSunnyWeatherEffect FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSunnyWeatherEffect and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WindDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Gets or sets the wind direction (0-359).</p>


```csharp
public int WindDirection { get; set; }
```
### WindSpeed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Gets or sets the wind speed in km/h.</p>


```csharp
public int WindSpeed { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSunnyWeatherEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


