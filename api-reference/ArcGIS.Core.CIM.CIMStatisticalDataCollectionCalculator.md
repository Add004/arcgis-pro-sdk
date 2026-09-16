# CIMStatisticalDataCollectionCalculator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionCalculator.yml" sourcestartlinenumber="1">Base class for statistical data collection calculator.</p>


## Object Signature

```csharp
public abstract class CIMStatisticalDataCollectionCalculator : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMStatisticalDataCollectionCalculator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionCalculator.yml" sourcestartlinenumber="1">Base class for statistical data collection calculator.</p>


```csharp
protected CIMStatisticalDataCollectionCalculator()
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionCalculator.yml" sourcestartlinenumber="1">Gets or sets the Name of the calculator.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionCalculator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMStatisticalDataCollectionCalculator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


