# CIMGraphicFrame

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Represents a graphic frame.</p>


## Object Signature

```csharp
public class CIMGraphicFrame : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGraphicFrame()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Represents a graphic frame.</p>


```csharp
public CIMGraphicFrame()
```
### BackgroundCornerRounding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the background corner rounding. 0 = fully square. 100 = fully round.</p>


```csharp
public double BackgroundCornerRounding { get; set; }
```
### BackgroundGapX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the background X gap.</p>


```csharp
public double BackgroundGapX { get; set; }
```
### BackgroundGapY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the background Y gap.</p>


```csharp
public double BackgroundGapY { get; set; }
```
### BackgroundSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the background symbol of the graphic frame.</p>


```csharp
public CIMSymbolReference BackgroundSymbol { get; set; }
```
### BorderCornerRounding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the border corner rounding. 0 = fully square. 100 = fully round.</p>


```csharp
public double BorderCornerRounding { get; set; }
```
### BorderGapX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the border X gap.</p>


```csharp
public double BorderGapX { get; set; }
```
### BorderGapY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the border Y gap.</p>


```csharp
public double BorderGapY { get; set; }
```
### BorderSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the border symbol of the graphic frame.</p>


```csharp
public CIMSymbolReference BorderSymbol { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGraphicFrame.</p>


```csharp
public CIMGraphicFrame Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Reconstructs the CIMGraphicFrame with a specified state from a JSON encoding.</p>


```csharp
public static CIMGraphicFrame FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ShadowCornerRounding

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the shadow corner rounding. 0 = fully square. 100 = fully round.</p>


```csharp
public double ShadowCornerRounding { get; set; }
```
### ShadowOffsetX

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the shadow X offset.</p>


```csharp
public double ShadowOffsetX { get; set; }
```
### ShadowOffsetY

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the shadow Y offset.</p>


```csharp
public double ShadowOffsetY { get; set; }
```
### ShadowSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Gets or sets the shadow symbol of the graphic frame.</p>


```csharp
public CIMSymbolReference ShadowSymbol { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGraphicFrame and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGraphicFrame.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


