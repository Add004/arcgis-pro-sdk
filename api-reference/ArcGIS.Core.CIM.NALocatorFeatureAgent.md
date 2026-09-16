# NALocatorFeatureAgent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Represents a network analyst locator feature agent. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NALocatorFeatureAgent : NALocatorAgent, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NALocatorFeatureAgent()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Creates a new default locator feature agent object.</p>


```csharp
public NALocatorFeatureAgent()
```
### NALocatorFeatureAgent(string, string, bool, int, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Creates a new default locator feature agent object from the input parameters.</p>


```csharp
public NALocatorFeatureAgent(string name, string whereClause = "", bool usesSubType = false, int subTypeCode = 0, int snapType = 0)
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Reconstructs the NALocatorFeatureAgent with a specified state from a JSON encoding.</p>


```csharp
public static NALocatorFeatureAgent FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Gets and sets the name of the locator agent.</p>


```csharp
public string Name { get; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SnapType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Gets and sets the method of snapping used.</p>


```csharp
public int SnapType { get; }
```
### SubtypeCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Gets and sets the subtype to be used to locate features.</p>


```csharp
public int SubtypeCode { get; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NALocatorFeatureAgent and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UsesSubtype

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if subtypes should be used to locate features.</p>


```csharp
public bool UsesSubtype { get; }
```
### WhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Gets and sets the where clause to filter candidate locations not including the subtype predicate in the UseSubtype case.</p>


```csharp
public string WhereClause { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorFeatureAgent.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


