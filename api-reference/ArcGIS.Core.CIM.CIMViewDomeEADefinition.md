# CIMViewDomeEADefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Represents a view dome exploratory analysis definition.</p>


## Object Signature

```csharp
public class CIMViewDomeEADefinition : CIMExploratoryAnalysisDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMViewDomeEADefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Represents a view dome exploratory analysis definition.</p>


```csharp
public CIMViewDomeEADefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMViewDomeEADefinition.</p>


```csharp
public CIMViewDomeEADefinition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMViewDomeEADefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMViewDomeEADefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Gets or sets the maximum distance to be analyzed.</p>


```csharp
public double MaximumDistance { get; set; }
```
### MinimumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Gets or sets the maximum distance to be analyzed.</p>


```csharp
public double MinimumDistance { get; set; }
```
### Observer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Gets or sets the observer position.</p>


```csharp
public MapPoint Observer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMViewDomeEADefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMViewDomeEADefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


