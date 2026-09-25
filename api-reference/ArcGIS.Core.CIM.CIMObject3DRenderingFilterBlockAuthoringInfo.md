# CIMObject3DRenderingFilterBlockAuthoringInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Represents a filter block authoring info.</p>


## Object Signature

```csharp
public class CIMObject3DRenderingFilterBlockAuthoringInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMObject3DRenderingFilterBlockAuthoringInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Represents a filter block authoring info.</p>


```csharp
public CIMObject3DRenderingFilterBlockAuthoringInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMObject3DRenderingFilterBlockAuthoringInfo.</p>


```csharp
public CIMObject3DRenderingFilterBlockAuthoringInfo Clone()
```
### FilterStates

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the filter state.</p>


```csharp
public CIMObject3DRenderingFilterState[] FilterStates { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMObject3DRenderingFilterBlockAuthoringInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMObject3DRenderingFilterBlockAuthoringInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMObject3DRenderingFilterBlockAuthoringInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlockAuthoringInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


