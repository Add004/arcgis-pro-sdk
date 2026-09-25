# CIMNetworkSourceDisplayFilter

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Represents a network source display filter.</p>


## Object Signature

```csharp
public class CIMNetworkSourceDisplayFilter : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkSourceDisplayFilter()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Represents a network source display filter.</p>


```csharp
public CIMNetworkSourceDisplayFilter()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkSourceDisplayFilter.</p>


```csharp
public CIMNetworkSourceDisplayFilter Clone()
```
### DefinitionExpression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Gets or sets the definition expression.</p>


```csharp
public string DefinitionExpression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkSourceDisplayFilter with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkSourceDisplayFilter FromJson(string json, JsonDeserializationSettings settings = null)
```
### NetworkSource

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Gets or sets the network source.</p>


```csharp
public string NetworkSource { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkSourceDisplayFilter and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the filter is visible.</p>


```csharp
public bool Visible { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkSourceDisplayFilter.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


