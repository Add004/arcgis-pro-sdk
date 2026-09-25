# CIMColorRamp

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorRamp.yml" sourcestartlinenumber="1">Supports color ramp schemes in the CIM model by providing low level access to properties common amongst all color ramp types.</p>


## Object Signature

```csharp
public abstract class CIMColorRamp : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorRamp.yml" sourcestartlinenumber="1">This is the base color ramp type which provides access to the color space.</p>


## Members

### CIMColorRamp()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorRamp.yml" sourcestartlinenumber="1">Supports color ramp schemes in the CIM model by providing low level access to properties common amongst all color ramp types.</p>


```csharp
protected CIMColorRamp()
```
### ColorSpace

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorRamp.yml" sourcestartlinenumber="1">Gets or sets the color space of the color.
This color space is defined by an ICC color profile.</p>


```csharp
public CIMColorSpace ColorSpace { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorRamp.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorRamp.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


