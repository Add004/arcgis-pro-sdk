# CIMInMemoryWorkspaceDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Represents an in-memory workspace data connection.</p>


## Object Signature

```csharp
public class CIMInMemoryWorkspaceDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMInMemoryWorkspaceDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Represents an in-memory workspace data connection.</p>


```csharp
public CIMInMemoryWorkspaceDataConnection()
```
### BinaryReferencePath

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Gets or sets the path to the binary reference containing the serialized workspace.</p>


```csharp
public string BinaryReferencePath { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMInMemoryWorkspaceDataConnection.</p>


```csharp
public CIMInMemoryWorkspaceDataConnection Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMInMemoryWorkspaceDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMInMemoryWorkspaceDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMInMemoryWorkspaceDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMInMemoryWorkspaceDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


