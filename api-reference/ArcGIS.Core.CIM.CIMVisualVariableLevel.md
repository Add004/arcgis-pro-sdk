# CIMVisualVariableLevel

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Represents a level-of-detail for a multilevel visual variable.</p>


## Object Signature

```csharp
public class CIMVisualVariableLevel : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMVisualVariableLevel()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Represents a level-of-detail for a multilevel visual variable.</p>


```csharp
public CIMVisualVariableLevel()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Creates a deep copy of CIMVisualVariableLevel.</p>


```csharp
public CIMVisualVariableLevel Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Reconstructs the CIMVisualVariableLevel with a specified state from a JSON encoding.</p>


```csharp
public static CIMVisualVariableLevel FromJson(string json, JsonDeserializationSettings settings = null)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Gets or sets the identifier of this level.</p>


```csharp
public int ID { get; set; }
```
### MaxValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Gets or sets the maximum value.</p>


```csharp
public double MaxValue { get; set; }
```
### Mean

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Gets or sets the cached mean of the data at this level. Used to rapidly compute new minimum and maximum values.</p>


```csharp
public double Mean { get; set; }
```
### MinValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Gets or sets the minimum value.</p>


```csharp
public double MinValue { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StandardDeviation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Gets or sets the cached standard deviation of the data at this level. Used to rapidly compute new minimum and maximum values.</p>


```csharp
public double StandardDeviation { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMVisualVariableLevel and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMVisualVariableLevel.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


