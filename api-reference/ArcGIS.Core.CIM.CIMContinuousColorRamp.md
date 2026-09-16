# CIMContinuousColorRamp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">Supports continuous color ramp schemes by providing low level access to properties common amongst all continuous color ramp types.</p>


## Object Signature

```csharp
public abstract class CIMContinuousColorRamp : CIMColorRamp, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">This is the base continuous color ramp type which primarily provides access to from and to colors.</p>


## Members

### CIMContinuousColorRamp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">Supports continuous color ramp schemes by providing low level access to properties common amongst all continuous color ramp types.</p>


```csharp
protected CIMContinuousColorRamp()
```
### FromColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">Gets or sets the beginning color for the color ramp (also known as a color scheme).</p>


```csharp
public CIMColor FromColor { get; set; }
```
### PrimitiveName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">Gets or sets the primitive name.</p>


```csharp
public string PrimitiveName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToColor

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">Gets or sets the ending color for the color ramp (also known as a color scheme). This is the color that the scheme transitions to.</p>


```csharp
public CIMColor ToColor { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMContinuousColorRamp.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


