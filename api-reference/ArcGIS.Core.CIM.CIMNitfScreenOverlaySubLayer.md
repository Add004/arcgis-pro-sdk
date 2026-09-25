# CIMNitfScreenOverlaySubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Represents NITF screen overlay.</p>


## Object Signature

```csharp
public class CIMNitfScreenOverlaySubLayer : CIMNitfImageSubLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNitfScreenOverlaySubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Represents NITF screen overlay.</p>


```csharp
public CIMNitfScreenOverlaySubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNitfScreenOverlaySubLayer.</p>


```csharp
public CIMNitfScreenOverlaySubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMNitfScreenOverlaySubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMNitfScreenOverlaySubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### Height

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Gets or sets the height (in pixels) of the screen overlay.</p>


```csharp
public double Height { get; set; }
```
### Left

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Gets or sets the position (in pixels) of the left side of the screen overlay.</p>


```csharp
public double Left { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNitfScreenOverlaySubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### Top

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Gets or sets the position (in pixels) of the top side of the screen overlay.</p>


```csharp
public double Top { get; set; }
```
### Width

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Gets or sets the width (in pixels) of the screen overlay.</p>


```csharp
public double Width { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNitfScreenOverlaySubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


