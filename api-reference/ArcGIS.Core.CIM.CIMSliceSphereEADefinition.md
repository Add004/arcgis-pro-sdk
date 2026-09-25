# CIMSliceSphereEADefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Represents a slice sphere exploratory analysis definition.</p>


## Object Signature

```csharp
public class CIMSliceSphereEADefinition : CIMExploratoryAnalysisDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMSliceSphereEADefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Represents a slice sphere exploratory analysis definition.</p>


```csharp
public CIMSliceSphereEADefinition()
```
### CenterPoint

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Gets or sets the observer position.</p>


```csharp
public MapPoint CenterPoint { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMSliceSphereEADefinition.</p>


```csharp
public CIMSliceSphereEADefinition Clone()
```
### CullDirection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Gets or sets the direction that is clipped.</p>


```csharp
public CullDirection CullDirection { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMSliceSphereEADefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMSliceSphereEADefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### Radius

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Gets or sets the analysis distance from the center position.</p>


```csharp
public double Radius { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMSliceSphereEADefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMSliceSphereEADefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


