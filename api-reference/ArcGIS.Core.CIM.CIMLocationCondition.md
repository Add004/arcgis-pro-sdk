# CIMLocationCondition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocationCondition.yml" sourcestartlinenumber="1">Represents a location condition.</p>


## Object Signature

```csharp
public abstract class CIMLocationCondition : CIMCondition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMLocationCondition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocationCondition.yml" sourcestartlinenumber="1">Represents a location condition.</p>


```csharp
protected CIMLocationCondition()
```
### ConditionType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocationCondition.yml" sourcestartlinenumber="1">Gets or sets the location condition type.</p>


```csharp
public LocationConditionType ConditionType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocationCondition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocationCondition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


