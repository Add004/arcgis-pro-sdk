# CIMStandardServiceConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Represents a standard service connection.</p>


## Object Signature

```csharp
public class CIMStandardServiceConnection : CIMServiceConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStandardServiceConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Represents a standard service connection.</p>


```csharp
public CIMStandardServiceConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMStandardServiceConnection.</p>


```csharp
public CIMStandardServiceConnection Clone()
```
### Culture

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the service culture.</p>


```csharp
public string Culture { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMStandardServiceConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMStandardServiceConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ServiceProvider

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the service provider.</p>


```csharp
public string ServiceProvider { get; set; }
```
### ServiceType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the service type.</p>


```csharp
public string ServiceType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMStandardServiceConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### URL

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Gets or sets the service URL.</p>


```csharp
public string URL { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStandardServiceConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


