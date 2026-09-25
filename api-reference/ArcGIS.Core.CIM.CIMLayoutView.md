# CIMLayoutView

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Represents a layout view in the project.</p>


## Object Signature

```csharp
public class CIMLayoutView : CIMView, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLayoutView()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Represents a layout view in the project.</p>


```csharp
public CIMLayoutView()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLayoutView.</p>


```csharp
public CIMLayoutView Clone()
```
### ColorVisionDeficiencyMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Gets or sets the color vision deficiency mode of the view.</p>


```csharp
public ColorVisionDeficiencyType ColorVisionDeficiencyMode { get; set; }
```
### DefaultMapFrameName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Gets or sets the default map for a view.</p>


```csharp
public string DefaultMapFrameName { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Gets or sets the extent for the view.</p>


```csharp
public Envelope Extent { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Reconstructs the CIMLayoutView with a specified state from a JSON encoding.</p>


```csharp
public static CIMLayoutView FromJson(string json, JsonDeserializationSettings settings = null)
```
### PauseDrawing

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether drawing is in the paused state for the view.</p>


```csharp
public bool PauseDrawing { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLayoutView and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLayoutView.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


