# NALocatorDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Represents a network analyst locator definition. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public abstract class NALocatorDefinition : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NALocatorDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Represents a network analyst locator definition. This class is reserved for esri internal use only.</p>


```csharp
protected NALocatorDefinition()
```
### AllowAutoRelocate

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates whether to turn on or off auto-relocate behavior at solve time.</p>


```csharp
public bool AllowAutoRelocate { get; set; }
```
### ExcludeRestrictedElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates whether to exclude restricted portions of the network when locating points.</p>


```csharp
[Obsolete("Deprecated at 3.3. Logically always true.")]
public bool ExcludeRestrictedElements { get; set; }
```
### FindClosest

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets a boolean which indicates if the closest location (only) should be returned.</p>


```csharp
[Obsolete("Deprecated at 3.3. Logically always true.")]
public bool FindClosest { get; set; }
```
### LocatorOverrides

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Input classes with an override locator use those locator settings instead of the default locator settings.</p>


```csharp
public CIMNALocatorOverrideClass[] LocatorOverrides { get; set; }
```
### MaxSnapTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets the maximum snap tolerance.</p>


```csharp
public double MaxSnapTolerance { get; set; }
```
### NALocatorAgents

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets the locator agents.</p>


```csharp
public NALocatorAgent[] NALocatorAgents { get; set; }
```
### OutputSpatialReference

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets the output spatial reference.</p>


```csharp
public SpatialReference OutputSpatialReference { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SnapTolerance

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets the snap tolerance.</p>


```csharp
public double SnapTolerance { get; set; }
```
### SnapToleranceUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Gets and sets the snap tolerance units.</p>


```csharp
public esriUnits SnapToleranceUnits { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocatorDefinition.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


