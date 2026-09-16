# CIMColorSpace

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSpace.yml" sourcestartlinenumber="1">Supports colors spaces by providing a common base type for all color spaces.</p>


## Object Signature

```csharp
public abstract class CIMColorSpace : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSpace.yml" sourcestartlinenumber="1">This is the base color space class.</p>


## Members

### CIMColorSpace()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSpace.yml" sourcestartlinenumber="1">Supports colors spaces by providing a common base type for all color spaces.</p>


```csharp
protected CIMColorSpace()
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSpace.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMColorSpace.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


