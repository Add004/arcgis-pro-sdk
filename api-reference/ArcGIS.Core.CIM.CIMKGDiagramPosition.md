# CIMKGDiagramPosition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Diagram Position.</p>


## Object Signature

```csharp
public class CIMKGDiagramPosition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMKGDiagramPosition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Represents a Knowledge Graph Diagram Position.</p>


```csharp
public CIMKGDiagramPosition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMKGDiagramPosition.</p>


```csharp
public CIMKGDiagramPosition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Reconstructs the CIMKGDiagramPosition with a specified state from a JSON encoding.</p>


```csharp
public static CIMKGDiagramPosition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMKGDiagramPosition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```
### X

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Gets or sets the x position within a diagram.</p>


```csharp
public double X { get; set; }
```
### Y

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMKGDiagramPosition.yml" sourcestartlinenumber="1">Gets or sets the y position within a diagram.</p>


```csharp
public double Y { get; set; }
```


