# CIMBASuitabilityAnalysisCriterion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis criterion.</p>


## Object Signature

```csharp
public abstract class CIMBASuitabilityAnalysisCriterion : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBASuitabilityAnalysisCriterion()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis criterion.</p>


```csharp
protected CIMBASuitabilityAnalysisCriterion()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the ID of the criterion.</p>


```csharp
public string ID { get; set; }
```
### IdealValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the ideal value of the criterion.</p>


```csharp
public double IdealValue { get; set; }
```
### Influence

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the influence of the criterion.</p>


```csharp
public BACriterionInfluence Influence { get; set; }
```
### IsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the criterion is enabled.</p>


```csharp
public bool IsEnabled { get; set; }
```
### IsLocked

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the criterion is locked.</p>


```csharp
public bool IsLocked { get; set; }
```
### Max

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the max of the criterion.</p>


```csharp
public double Max { get; set; }
```
### Min

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the min of the criterion.</p>


```csharp
public double Min { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### TargetValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the calculated value of the Target Site of the criterion.</p>


```csharp
public double TargetValue { get; set; }
```
### Title

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the title of the criterion.</p>


```csharp
public string Title { get; set; }
```
### ValueField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the value of the criterion.</p>


```csharp
public string ValueField { get; set; }
```
### Weight

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Gets or sets the weight of the criterion.</p>


```csharp
public double Weight { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisCriterion.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


