# CIMColorModulationInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Indicates whether modulation should be used to render the point. Low modulation values will darken the point color.</p>


## Object Signature

```csharp
public class CIMColorModulationInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMColorModulationInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Indicates whether modulation should be used to render the point. Low modulation values will darken the point color.</p>


```csharp
public CIMColorModulationInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMColorModulationInfo.</p>


```csharp
public CIMColorModulationInfo Clone()
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Gets or sets the attribute to use as a source for the color modulation.</p>


```csharp
public string Field { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMColorModulationInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMColorModulationInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### MaxValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Gets or sets the maximum value to compute modulation on linear scale based on field value.</p>


```csharp
public double MaxValue { get; set; }
```
### MinValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Gets or sets the minimum value to compute modulation on linear scale based on field value.</p>


```csharp
public double MinValue { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMColorModulationInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorModulationInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


