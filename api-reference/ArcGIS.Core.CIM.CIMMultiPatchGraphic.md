# CIMMultiPatchGraphic

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Represents a shape graphic with a MultiPatch geometry.</p>


## Object Signature

```csharp
public class CIMMultiPatchGraphic : CIMShapeGraphic, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultiPatchGraphic()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Represents a shape graphic with a MultiPatch geometry.</p>


```csharp
public CIMMultiPatchGraphic()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMultiPatchGraphic.</p>


```csharp
public CIMMultiPatchGraphic Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Reconstructs the CIMMultiPatchGraphic with a specified state from a JSON encoding.</p>


```csharp
public static CIMMultiPatchGraphic FromJson(string json, JsonDeserializationSettings settings = null)
```
### MultiPatch

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Gets or sets the graphic's MultiPatch geometry.</p>


```csharp
public Multipatch MultiPatch { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMultiPatchGraphic and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultiPatchGraphic.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


