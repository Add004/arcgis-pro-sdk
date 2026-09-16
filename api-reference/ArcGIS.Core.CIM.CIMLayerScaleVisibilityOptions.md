# CIMLayerScaleVisibilityOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Represents a layer's scale visibility options.</p>


## Object Signature

```csharp
public class CIMLayerScaleVisibilityOptions : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLayerScaleVisibilityOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Represents a layer's scale visibility options.</p>


```csharp
public CIMLayerScaleVisibilityOptions()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayerScaleVisibilityOptions.</p>


```csharp
public CIMLayerScaleVisibilityOptions Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Reconstructs the CIMLayerScaleVisibilityOptions with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayerScaleVisibilityOptions FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SavedMaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Gets or sets the maximum scale that is saved when ShowLayerAtAllScales is set to true.</p>


```csharp
public double SavedMaxScale { get; set; }
```
### SavedMinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Gets or sets the minimum scale that is saved when ShowLayerAtAllScales is set to true.</p>


```csharp
public double SavedMinScale { get; set; }
```
### ShowLayerAtAllScales

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the layer is visible at all scales.</p>


```csharp
public bool ShowLayerAtAllScales { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayerScaleVisibilityOptions and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayerScaleVisibilityOptions.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


