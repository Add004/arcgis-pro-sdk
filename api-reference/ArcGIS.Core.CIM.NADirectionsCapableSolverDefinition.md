# NADirectionsCapableSolverDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Represents a solver definition that can support directions configurations. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public abstract class NADirectionsCapableSolverDefinition : NASolverDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NADirectionsCapableSolverDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Represents a solver definition that can support directions configurations. This class is reserved for esri internal use only.</p>


```csharp
protected NADirectionsCapableSolverDefinition()
```
### DirectionsLanguage

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the directions language.</p>


```csharp
public string DirectionsLanguage { get; }
```
### DirectionsLengthAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the directions length attribute name.</p>


```csharp
public string DirectionsLengthAttributeName { get; }
```
### DirectionsLengthUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the directions length units.</p>


```csharp
public esriNetworkAttributeUnits DirectionsLengthUnits { get; }
```
### DirectionsOutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the directions output spatial reference.</p>


```csharp
public SpatialReference DirectionsOutputSpatialReference { get; }
```
### DirectionsOutputType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the directions output type.</p>


```csharp
public esriDirectionsOutputType DirectionsOutputType { get; }
```
### DirectionsStyleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the directions style name.</p>


```csharp
public string DirectionsStyleName { get; }
```
### DirectionsTimeAttributeName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets the directions time attribute name.</p>


```csharp
public string DirectionsTimeAttributeName { get; }
```
### IsDirectionsGenerationEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Gets and sets whether or not to generate directions on solve.</p>


```csharp
public bool IsDirectionsGenerationEnabled { get; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NADirectionsCapableSolverDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


