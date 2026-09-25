# CIMPresentationLayerOverrideSet

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Represents a presentation layer property override set.</p>


## Object Signature

```csharp
public class CIMPresentationLayerOverrideSet : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPresentationLayerOverrideSet()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Represents a presentation layer property override set.</p>


```csharp
public CIMPresentationLayerOverrideSet()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentationLayerOverrideSet.</p>


```csharp
public CIMPresentationLayerOverrideSet Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentationLayerOverrideSet with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentationLayerOverrideSet FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Gets or sets the path to the associated map layer.</p>


```csharp
public string LayerURI { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentationLayerOverrideSet and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Visibility

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this layer is visible. It overrides the visibility property on the associated map layer.</p>


```csharp
public bool Visibility { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationLayerOverrideSet.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


