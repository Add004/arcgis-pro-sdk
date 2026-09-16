# CIMMultilevelVisualVariable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelVisualVariable.yml" sourcestartlinenumber="1">Represents a visual variable with different levels-of-detail, each with its own minimum and maximum data values. Used for binning layers.</p>


## Object Signature

```csharp
public abstract class CIMMultilevelVisualVariable : CIMVisualVariable, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMultilevelVisualVariable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelVisualVariable.yml" sourcestartlinenumber="1">Represents a visual variable with different levels-of-detail, each with its own minimum and maximum data values. Used for binning layers.</p>


```csharp
protected CIMMultilevelVisualVariable()
```
### Levels

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelVisualVariable.yml" sourcestartlinenumber="1">Gets or sets the levels that hold the minimum and maximum values of the data.</p>


```csharp
public CIMVisualVariableLevel[] Levels { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelVisualVariable.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMultilevelVisualVariable.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


