# CIMParcelFabricActiveRecord

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Defines the parcel fabric active record properties needed for record-driven parcel workflows.</p>


## Object Signature

```csharp
public class CIMParcelFabricActiveRecord : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMParcelFabricActiveRecord()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Defines the parcel fabric active record properties needed for record-driven parcel workflows.</p>


```csharp
public CIMParcelFabricActiveRecord()
```
### ActiveRecord

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Gets or sets the active record GlobalID.</p>


```csharp
public string ActiveRecord { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Creates a deep copy of CIMParcelFabricActiveRecord.</p>


```csharp
public CIMParcelFabricActiveRecord Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not there is an active record.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Reconstructs the CIMParcelFabricActiveRecord with a specified state from a JSON encoding.</p>


```csharp
public static CIMParcelFabricActiveRecord FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShowActiveRecordOnly

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether to show only the features associated with the active record in the map.</p>


```csharp
public bool ShowActiveRecordOnly { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMParcelFabricActiveRecord and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMParcelFabricActiveRecord.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


