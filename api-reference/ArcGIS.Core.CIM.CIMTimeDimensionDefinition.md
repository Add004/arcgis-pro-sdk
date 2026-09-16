# CIMTimeDimensionDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Represents a time dimension definition.</p>


## Object Signature

```csharp
public class CIMTimeDimensionDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTimeDimensionDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Represents a time dimension definition.</p>


```csharp
public CIMTimeDimensionDefinition()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTimeDimensionDefinition.</p>


```csharp
public CIMTimeDimensionDefinition Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Reconstructs the CIMTimeDimensionDefinition with a specified state from a JSON encoding.</p>


```csharp
public static CIMTimeDimensionDefinition FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TimeDimensionFormat

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Gets or sets the time dimension format.</p>


```csharp
public string TimeDimensionFormat { get; set; }
```
### TimeDimensionName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Gets or sets the time dimension name.</p>


```csharp
public string TimeDimensionName { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTimeDimensionDefinition and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTimeDimensionDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


