# CIMTinNodeValueRenderer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinNodeValueRenderer.yml" sourcestartlinenumber="1">Represents a TIN node value renderer.</p>


## Object Signature

```csharp
public class CIMTinNodeValueRenderer : CIMTinUniqueValueRenderer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMTinNodeValueRenderer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinNodeValueRenderer.yml" sourcestartlinenumber="1">Represents a TIN node value renderer.</p>


```csharp
public CIMTinNodeValueRenderer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinNodeValueRenderer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMTinNodeValueRenderer.</p>


```csharp
public CIMTinNodeValueRenderer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinNodeValueRenderer.yml" sourcestartlinenumber="1">Reconstructs the CIMTinNodeValueRenderer with a specified state from a JSON encoding.</p>


```csharp
public static CIMTinNodeValueRenderer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinNodeValueRenderer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinNodeValueRenderer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMTinNodeValueRenderer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMTinNodeValueRenderer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


