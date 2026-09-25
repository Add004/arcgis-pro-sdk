# CIMFeatureReduction

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for visually reducing large numbers of features in a map.</p>


## Object Signature

```csharp
public abstract class CIMFeatureReduction : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFeatureReduction()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for visually reducing large numbers of features in a map.</p>


```csharp
protected CIMFeatureReduction()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether feature reduction is enabled in the feature layer.</p>


```csharp
public bool Enabled { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureReduction.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFeatureReduction.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


