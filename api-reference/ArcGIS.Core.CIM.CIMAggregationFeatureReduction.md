# CIMAggregationFeatureReduction

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregationFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for visually reducing large numbers of features in a map by aggregating them.</p>


## Object Signature

```csharp
public abstract class CIMAggregationFeatureReduction : CIMFeatureReduction, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMAggregationFeatureReduction()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregationFeatureReduction.yml" sourcestartlinenumber="1">Represents a technique for visually reducing large numbers of features in a map by aggregating them.</p>


```csharp
protected CIMAggregationFeatureReduction()
```
### Fields

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregationFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the fields that should be shown with the aggregated features.</p>


```csharp
public CIMAggregateField[] Fields { get; set; }
```
### PopupInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregationFeatureReduction.yml" sourcestartlinenumber="1">Gets or sets the popup info for the aggregated features.</p>


```csharp
public CIMPopupInfo PopupInfo { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregationFeatureReduction.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMAggregationFeatureReduction.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


