# CIMLineOfSightEADefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Represents a line of sight exploratory analysis definition.</p>


## Object Signature

```csharp
public class CIMLineOfSightEADefinition : CIMExploratoryAnalysisDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLineOfSightEADefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Represents a line of sight exploratory analysis definition.</p>


```csharp
public CIMLineOfSightEADefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLineOfSightEADefinition.</p>


```csharp
public CIMLineOfSightEADefinition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMLineOfSightEADefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMLineOfSightEADefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaximumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Gets or sets the maximum distance to be analyzed.</p>


```csharp
public double MaximumDistance { get; set; }
```
### MinimumDistance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Gets or sets the minimum distance to be analyzed.</p>


```csharp
public double MinimumDistance { get; set; }
```
### Observer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Gets or sets the observer position.</p>


```csharp
public MapPoint Observer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Targets

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Gets or sets the target positions.</p>


```csharp
public Multipoint Targets { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLineOfSightEADefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLineOfSightEADefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


