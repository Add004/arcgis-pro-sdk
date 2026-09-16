# CIMObject3DRenderingFilterBlock

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Represents a 3D object rendering filter block.</p>


## Object Signature

```csharp
public class CIMObject3DRenderingFilterBlock : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMObject3DRenderingFilterBlock()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Represents a 3D object rendering filter block.</p>


```csharp
public CIMObject3DRenderingFilterBlock()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Creates a deep copy of CIMObject3DRenderingFilterBlock.</p>


```csharp
public CIMObject3DRenderingFilterBlock Clone()
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Gets or sets the expression.</p>


```csharp
public string Expression { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Reconstructs the CIMObject3DRenderingFilterBlock with a specified state from a JSON encoding.</p>


```csharp
public static CIMObject3DRenderingFilterBlock FromJson(string json, JsonDeserializationSettings settings = null)
```
### Mode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Gets or sets the rendering mode.</p>


```csharp
public Object3DRenderingMode Mode { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Gets or sets the title.</p>


```csharp
public string Title { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMObject3DRenderingFilterBlock and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterBlock.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


