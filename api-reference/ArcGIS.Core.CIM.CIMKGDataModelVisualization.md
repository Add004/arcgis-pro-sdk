# CIMKGDataModelVisualization

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Model Visualization.</p>


## Object Signature

```csharp
public class CIMKGDataModelVisualization : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGDataModelVisualization()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Data Model Visualization.</p>


```csharp
public CIMKGDataModelVisualization()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGDataModelVisualization.</p>


```csharp
public CIMKGDataModelVisualization Clone()
```
### ConfigurationName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Gets or sets the name of the Data Model Visualization.
Names are expected to be unique within an Investigation.</p>


```csharp
public string ConfigurationName { get; set; }
```
### EntityTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Gets or sets the configured entity types.</p>


```csharp
public CIMKGEntityType[] EntityTypes { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Reconstructs the CIMKGDataModelVisualization with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGDataModelVisualization FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RelationshipTypes

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Gets or sets the configured relationship types.</p>


```csharp
public CIMKGRelationshipType[] RelationshipTypes { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGDataModelVisualization and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDataModelVisualization.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


