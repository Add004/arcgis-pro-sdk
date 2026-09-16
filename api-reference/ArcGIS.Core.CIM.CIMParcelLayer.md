# CIMParcelLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Represents a parcel fabric layer.</p>


## Object Signature

```csharp
public class CIMParcelLayer : CIMBaseLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMParcelLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Represents a parcel fabric layer.</p>


```csharp
public CIMParcelLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMParcelLayer.</p>


```csharp
public CIMParcelLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMParcelLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMParcelLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ParcelConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Gets or sets the data connection to the Parcel Fabric. A Parcel Fabric controls simple feature
classes and uses topology rules and parcel rules. Parcel geometry is edited using feature services
The Parcel Layer provides additional services to control the fabric classes such as validate.</p>


```csharp
public CIMDataConnection ParcelConnection { get; set; }
```
### ParcelFabricActiveRecord

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Gets or sets the Parcel Fabric Active Record properties.</p>


```csharp
public CIMParcelFabricActiveRecord ParcelFabricActiveRecord { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RecordsLayer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Gets or sets the path to the parcel polygon records layer. The records layer links parcel
polygons and lines to the legal record that created / retired it as well as integration point
to business systems.</p>


```csharp
public string RecordsLayer { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMParcelLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


