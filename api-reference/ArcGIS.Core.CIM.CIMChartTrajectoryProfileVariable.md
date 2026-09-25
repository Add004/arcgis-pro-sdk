# CIMChartTrajectoryProfileVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Represents the definition of a variable for which data is to be plotted.</p>


## Object Signature

```csharp
public class CIMChartTrajectoryProfileVariable : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMChartTrajectoryProfileVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Represents the definition of a variable for which data is to be plotted.</p>


```csharp
public CIMChartTrajectoryProfileVariable()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Creates a deep copy of CIMChartTrajectoryProfileVariable.</p>


```csharp
public CIMChartTrajectoryProfileVariable Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this variable is enabled or not.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Reconstructs the CIMChartTrajectoryProfileVariable with a specified state from a JSON encoding.</p>


```csharp
public static CIMChartTrajectoryProfileVariable FromJson(string json, JsonDeserializationSettings settings = null)
```
### Label

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Gets or sets the variable label.</p>


```csharp
public string Label { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Gets or sets the variable name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Symbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Gets or sets the variable symbol.</p>


```csharp
public CIMSymbolReference Symbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMChartTrajectoryProfileVariable and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMChartTrajectoryProfileVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


