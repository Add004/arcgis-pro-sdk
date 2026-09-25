# CIMProportionalRendererAuthoringInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Represents additional authoring properties used by a proportional renderer.</p>


## Object Signature

```csharp
public class CIMProportionalRendererAuthoringInfo : CIMRendererAuthoringInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMProportionalRendererAuthoringInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Represents additional authoring properties used by a proportional renderer.</p>


```csharp
public CIMProportionalRendererAuthoringInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMProportionalRendererAuthoringInfo.</p>


```csharp
public CIMProportionalRendererAuthoringInfo Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMProportionalRendererAuthoringInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMProportionalRendererAuthoringInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### NumberOfHistogramBins

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the number of bins displayed in the histogram.</p>


```csharp
public int NumberOfHistogramBins { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMProportionalRendererAuthoringInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMProportionalRendererAuthoringInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


