# CIMAltitudeParams

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Represents altitude parameters.</p>


## Object Signature

```csharp
public class CIMAltitudeParams : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAltitudeParams()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Represents altitude parameters.</p>


```csharp
public CIMAltitudeParams()
```
### AltitudeValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Gets or sets the altitude value.</p>


```csharp
public double AltitudeValue { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Creates a deep copy of CIMAltitudeParams.</p>


```csharp
public CIMAltitudeParams Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Reconstructs the CIMAltitudeParams with a specified state from a JSON encoding.</p>


```csharp
public static CIMAltitudeParams FromJson(string json, JsonDeserializationSettings settings = null)
```
### Mode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Gets or sets the altitude mode.</p>


```csharp
public AltitudeMode Mode { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMAltitudeParams and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAltitudeParams.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


