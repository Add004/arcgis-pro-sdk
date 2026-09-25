# CIMMapPresentationPage

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Represents a map presentation page.</p>


## Object Signature

```csharp
public class CIMMapPresentationPage : CIMPresentationPage, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapPresentationPage()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Represents a map presentation page.</p>


```csharp
public CIMMapPresentationPage()
```
### AutoPlayAnimationName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the name of the animation that will automatically play when this map page becomes active.</p>


```csharp
public string AutoPlayAnimationName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Creates a deep copy of CIMMapPresentationPage.</p>


```csharp
public CIMMapPresentationPage Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Reconstructs the CIMMapPresentationPage with a specified state from a JSON encoding.</p>


```csharp
public static CIMMapPresentationPage FromJson(string json, JsonDeserializationSettings settings = null)
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the map view.</p>


```csharp
public CIMPresentationMapView MapView { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RestingState

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Gets or sets the map resting state.</p>


```csharp
public CIMPresentationMapRestingState RestingState { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMMapPresentationPage and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapPresentationPage.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


