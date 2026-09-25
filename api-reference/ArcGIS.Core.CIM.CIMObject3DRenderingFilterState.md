# CIMObject3DRenderingFilterState

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Represents a 3D object rendering filter value.</p>


## Object Signature

```csharp
public class CIMObject3DRenderingFilterState : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMObject3DRenderingFilterState()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Represents a 3D object rendering filter value.</p>


```csharp
public CIMObject3DRenderingFilterState()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Creates a deep copy of CIMObject3DRenderingFilterState.</p>


```csharp
public CIMObject3DRenderingFilterState Clone()
```
### FilterType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Gets or sets the filter type.</p>


```csharp
public string FilterType { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Reconstructs the CIMObject3DRenderingFilterState with a specified state from a JSON encoding.</p>


```csharp
public static CIMObject3DRenderingFilterState FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SelectedValues

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Gets or sets the selected values.</p>


```csharp
public string[] SelectedValues { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMObject3DRenderingFilterState and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMObject3DRenderingFilterState.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


