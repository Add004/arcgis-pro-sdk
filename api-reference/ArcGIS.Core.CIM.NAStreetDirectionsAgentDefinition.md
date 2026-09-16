# NAStreetDirectionsAgentDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Represents a network analyst street directions agent definition. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public abstract class NAStreetDirectionsAgentDefinition : NAAgent, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NAStreetDirectionsAgentDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Represents a network analyst street directions agent definition. This class is reserved for esri internal use only.</p>


```csharp
protected NAStreetDirectionsAgentDefinition()
```
### Language

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Gets and sets the language to use when generating directions.</p>


```csharp
public string Language { get; set; }
```
### LengthUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Gets and sets the length units.</p>


```csharp
public esriNetworkAttributeUnits LengthUnits { get; set; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public SpatialReference OutputSpatialReference { get; set; }
```
### OutputType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Gets and sets the type of line(s) generated.</p>


```csharp
public esriDirectionsOutputType OutputType { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### StyleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Gets and sets the style name to use when generating directions.</p>


```csharp
public string StyleName { get; set; }
```
### TimeAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Gets and sets the network attribute for time calculation.</p>


```csharp
public string TimeAttributeName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NAStreetDirectionsAgentDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


