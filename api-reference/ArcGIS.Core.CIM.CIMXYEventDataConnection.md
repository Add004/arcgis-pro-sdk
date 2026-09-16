# CIMXYEventDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Represents an XY event data connection.</p>


## Object Signature

```csharp
public class CIMXYEventDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMXYEventDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Represents an XY event data connection.</p>


```csharp
public CIMXYEventDataConnection()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMXYEventDataConnection.</p>


```csharp
public CIMXYEventDataConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMXYEventDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMXYEventDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the spatial reference.</p>


```csharp
public SpatialReference SpatialReference { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMXYEventDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### XFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the X field name.</p>


```csharp
public string XFieldName { get; set; }
```
### XYEventTableDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the data connection to the table events are created from.</p>


```csharp
public CIMDataConnection XYEventTableDataConnection { get; set; }
```
### YFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the Y field name.</p>


```csharp
public string YFieldName { get; set; }
```
### ZFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMXYEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the Z field name.</p>


```csharp
public string ZFieldName { get; set; }
```


