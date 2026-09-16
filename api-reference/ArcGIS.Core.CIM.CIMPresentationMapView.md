# CIMPresentationMapView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Represents a map view in a map presentation page.</p>


## Object Signature

```csharp
public class CIMPresentationMapView : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMPresentationMapView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Represents a map view in a map presentation page.</p>


```csharp
public CIMPresentationMapView()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Creates a deep copy of CIMPresentationMapView.</p>


```csharp
public CIMPresentationMapView Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Reconstructs the CIMPresentationMapView with a specified state from a JSON encoding.</p>


```csharp
public static CIMPresentationMapView FromJson(string json, JsonDeserializationSettings settings = null)
```
### LayerOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Gets or sets the array of layer overrides.</p>


```csharp
public CIMPresentationLayerOverrideSet[] LayerOverrides { get; set; }
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Gets or sets the map view.</p>


```csharp
public CIMMapView MapView { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMPresentationMapView and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMPresentationMapView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


