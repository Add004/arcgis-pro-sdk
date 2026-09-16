# CIMDisplayUnitSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Represents the display unit settings for the project.</p>


## Object Signature

```csharp
public class CIMDisplayUnitSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDisplayUnitSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Represents the display unit settings for the project.</p>


```csharp
public CIMDisplayUnitSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDisplayUnitSettings.</p>


```csharp
public CIMDisplayUnitSettings Clone()
```
### DirectionUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for direction units.</p>


```csharp
public CIMDisplayUnitCategory DirectionUnitCategory { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMDisplayUnitSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMDisplayUnitSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### LocationUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for location units.</p>


```csharp
public CIMDisplayUnitCategory LocationUnitCategory { get; set; }
```
### MapAngularUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for angular units.</p>


```csharp
public CIMDisplayUnitCategory MapAngularUnitCategory { get; set; }
```
### MapAreaUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for area units.</p>


```csharp
public CIMDisplayUnitCategory MapAreaUnitCategory { get; set; }
```
### MapLinearUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for linear units.</p>


```csharp
public CIMDisplayUnitCategory MapLinearUnitCategory { get; set; }
```
### PageUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for page units.</p>


```csharp
public CIMDisplayUnitCategory PageUnitCategory { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol2DUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for 2D symbol units.</p>


```csharp
public CIMDisplayUnitCategory Symbol2DUnitCategory { get; set; }
```
### Symbol3DUnitCategory

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Gets or sets the display settings for 3D symbol units.</p>


```csharp
public CIMDisplayUnitCategory Symbol3DUnitCategory { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDisplayUnitSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDisplayUnitSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


