# CIMDualScaleBar

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Represents a dual scale bar on a page layout.</p>


## Object Signature

```csharp
public class CIMDualScaleBar : CIMScaleBar, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMDualScaleBar()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Represents a dual scale bar on a page layout.</p>


```csharp
public CIMDualScaleBar()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Creates a deep copy of CIMDualScaleBar.</p>


```csharp
public CIMDualScaleBar Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Reconstructs the CIMDualScaleBar with a specified state from a JSON encoding.</p>


```csharp
public static CIMDualScaleBar FromJson(string json, JsonDeserializationSettings settings = null)
```
### LowerScaleBar

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Gets or sets the lower scale bar of the dual scale bar.</p>


```csharp
public CIMScaleBar LowerScaleBar { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMDualScaleBar and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### UnitLabelVerticalGap

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Gets or sets the unit label vertical gap. Units set in points.</p>


```csharp
public double UnitLabelVerticalGap { get; set; }
```
### UpperScaleBar

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Gets or sets the upper scale bar of the dual scale bar.</p>


```csharp
public CIMScaleBar UpperScaleBar { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMDualScaleBar.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


