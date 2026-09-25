# CIMWeatherEffect

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMWeatherEffect.yml" sourcestartlinenumber="1">Represents a weather effect to be applied to a scene.</p>


## Object Signature

```csharp
public abstract class CIMWeatherEffect : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMWeatherEffect()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMWeatherEffect.yml" sourcestartlinenumber="1">Represents a weather effect to be applied to a scene.</p>


```csharp
protected CIMWeatherEffect()
```
### IsActive

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWeatherEffect.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the effect should be applied to the scene.</p>


```csharp
public bool IsActive { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWeatherEffect.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Seed

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMWeatherEffect.yml" sourcestartlinenumber="1">Gets or sets the starting value for generating a random cloud pattern.</p>


```csharp
public int Seed { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMWeatherEffect.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


