# NAStreetDirectionsAgent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgent.yml" sourcestartlinenumber="1">Represents a network analyst street directions agent. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NAStreetDirectionsAgent : NAStreetDirectionsAgentDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAStreetDirectionsAgent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgent.yml" sourcestartlinenumber="1">Represents a network analyst street directions agent. This class is reserved for esri internal use only.</p>


```csharp
public NAStreetDirectionsAgent()
```
### DisplayTime

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgent.yml" sourcestartlinenumber="1">Get and sets a boolean which indicates if time is displayed in directions.</p>


```csharp
public bool DisplayTime { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgent.yml" sourcestartlinenumber="1">Reconstructs the NAStreetDirectionsAgent with a specified state from a JSON encoding.</p>


```csharp
public static NAStreetDirectionsAgent FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgent.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgent.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NAStreetDirectionsAgent and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgent.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


