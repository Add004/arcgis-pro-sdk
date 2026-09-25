# CIMColorReplacementRule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Represents a color replacement rule.</p>


## Object Signature

```csharp
public class CIMColorReplacementRule : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMColorReplacementRule()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Represents a color replacement rule.</p>


```csharp
public CIMColorReplacementRule()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Creates a deep copy of CIMColorReplacementRule.</p>


```csharp
public CIMColorReplacementRule Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Reconstructs the CIMColorReplacementRule with a specified state from a JSON encoding.</p>


```csharp
public static CIMColorReplacementRule FromJson(string json, JsonDeserializationSettings settings = null)
```
### InputColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Gets or sets the color that needs to be replaced.</p>


```csharp
public CIMColor InputColor { get; set; }
```
### OutputColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Gets or sets the color that will replace the input color.</p>


```csharp
public CIMColor OutputColor { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMColorReplacementRule and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorReplacementRule.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


