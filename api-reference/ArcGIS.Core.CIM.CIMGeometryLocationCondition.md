# CIMGeometryLocationCondition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Represents geometry location condition.</p>


## Object Signature

```csharp
public class CIMGeometryLocationCondition : CIMLocationCondition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeometryLocationCondition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Represents geometry location condition.</p>


```csharp
public CIMGeometryLocationCondition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeometryLocationCondition.</p>


```csharp
public CIMGeometryLocationCondition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Reconstructs the CIMGeometryLocationCondition with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeometryLocationCondition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Geometries

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Gets or sets the geometries.</p>


```csharp
public Geometry[] Geometries { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeometryLocationCondition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeometryLocationCondition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


