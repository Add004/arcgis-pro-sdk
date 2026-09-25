# CIMLayerRange

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Represents a layer range.</p>


## Object Signature

```csharp
public class CIMLayerRange : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLayerRange()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Represents a layer range.</p>


```csharp
public CIMLayerRange()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayerRange.</p>


```csharp
public CIMLayerRange Clone()
```
### CurrentRange

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Gets or sets the current range.</p>


```csharp
public CIMRange CurrentRange { get; set; }
```
### CurrentRangeRelation

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Gets or sets the current range relation.</p>


```csharp
public RangeRelation CurrentRangeRelation { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Reconstructs the CIMLayerRange with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayerRange FromJson(string json, JsonDeserializationSettings settings = null)
```
### IsExclusion

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is an exclusion range.</p>


```csharp
public bool IsExclusion { get; set; }
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Gets or sets the URI of the layer this range is defined for.</p>


```csharp
public string LayerURI { get; set; }
```
### RangeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Gets or sets the range name.</p>


```csharp
public string RangeName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayerRange and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerRange.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


