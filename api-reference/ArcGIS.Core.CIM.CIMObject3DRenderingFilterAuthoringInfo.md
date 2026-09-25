# CIMObject3DRenderingFilterAuthoringInfo

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Represents a filter authoring info.</p>


## Object Signature

```csharp
public class CIMObject3DRenderingFilterAuthoringInfo : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMObject3DRenderingFilterAuthoringInfo()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Represents a filter authoring info.</p>


```csharp
public CIMObject3DRenderingFilterAuthoringInfo()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Creates a deep copy of CIMObject3DRenderingFilterAuthoringInfo.</p>


```csharp
public CIMObject3DRenderingFilterAuthoringInfo Clone()
```
### FilterBlocks

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets the filter blocks.</p>


```csharp
public CIMObject3DRenderingFilterBlockAuthoringInfo[] FilterBlocks { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Reconstructs the CIMObject3DRenderingFilterAuthoringInfo with a specified state from a JSON encoding.</p>


```csharp
public static CIMObject3DRenderingFilterAuthoringInfo FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the filter is displayed in the UI or not.</p>


```csharp
public bool IsVisible { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMObject3DRenderingFilterAuthoringInfo and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterAuthoringInfo.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


