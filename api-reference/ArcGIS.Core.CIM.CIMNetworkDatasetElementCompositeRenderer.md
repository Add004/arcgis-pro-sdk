# CIMNetworkDatasetElementCompositeRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Represents a network dataset element composite renderer.</p>


## Object Signature

```csharp
public class CIMNetworkDatasetElementCompositeRenderer : CIMNetworkDatasetRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkDatasetElementCompositeRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Represents a network dataset element composite renderer.</p>


```csharp
public CIMNetworkDatasetElementCompositeRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkDatasetElementCompositeRenderer.</p>


```csharp
public CIMNetworkDatasetElementCompositeRenderer Clone()
```
### EdgeLineRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Gets or sets edge line renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer EdgeLineRenderer { get; set; }
```
### EdgePointRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Gets or sets edge point renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer EdgePointRenderer { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkDatasetElementCompositeRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkDatasetElementCompositeRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### JunctionPointRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Gets or sets junction point renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer JunctionPointRenderer { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkDatasetElementCompositeRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TurnLineRenderer

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Gets or sets turn line renderer.</p>


```csharp
public CIMNetworkDatasetSimpleRenderer TurnLineRenderer { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkDatasetElementCompositeRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


