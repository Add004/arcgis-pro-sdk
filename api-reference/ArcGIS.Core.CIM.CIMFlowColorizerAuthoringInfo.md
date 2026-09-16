# CIMFlowColorizerAuthoringInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Represents additional authoring properties used by a raster flow colorizer.</p>


## Object Signature

```csharp
public class CIMFlowColorizerAuthoringInfo : CIMRendererAuthoringInfo, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFlowColorizerAuthoringInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Represents additional authoring properties used by a raster flow colorizer.</p>


```csharp
public CIMFlowColorizerAuthoringInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFlowColorizerAuthoringInfo.</p>


```csharp
public CIMFlowColorizerAuthoringInfo Clone()
```
### FlowTheme

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the flow theme.</p>


```csharp
public FlowTheme FlowTheme { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMFlowColorizerAuthoringInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMFlowColorizerAuthoringInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFlowColorizerAuthoringInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### VisualVariables

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the visual variable authoring info. Used to preserve slider range and theme selections for each visual variable.</p>


```csharp
public CIMVisualVariableAuthoringInfo[] VisualVariables { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFlowColorizerAuthoringInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


