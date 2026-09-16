# NALocatorLocationFieldsAgent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Represents a network analyst locator location fields agent. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NALocatorLocationFieldsAgent : NALocatorAgent, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NALocatorLocationFieldsAgent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Represents a network analyst locator location fields agent. This class is reserved for esri internal use only.</p>


```csharp
public NALocatorLocationFieldsAgent()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Reconstructs the NALocatorLocationFieldsAgent with a specified state from a JSON encoding.</p>


```csharp
public static NALocatorLocationFieldsAgent FromJson(string json, JsonDeserializationSettings settings = null)
```
### LocationRangesFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Gets and sets the location ranges field name.</p>


```csharp
public string LocationRangesFieldName { get; set; }
```
### OIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Gets and sets the OID field name.</p>


```csharp
public string OIDFieldName { get; set; }
```
### PositionFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Gets and sets the position field name.</p>


```csharp
public string PositionFieldName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SideFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Gets and sets the side field name.</p>


```csharp
public string SideFieldName { get; set; }
```
### SourceIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Gets and sets the source ID field name.</p>


```csharp
public string SourceIDFieldName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NALocatorLocationFieldsAgent and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorLocationFieldsAgent.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


