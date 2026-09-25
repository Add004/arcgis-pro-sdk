# CIMMapGrid

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Represents a grid object for a map frame.</p>


## Object Signature

```csharp
public abstract class CIMMapGrid : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMMapGrid()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Represents a grid object for a map frame.</p>


```csharp
protected CIMMapGrid()
```
### EdgeMinimumLength

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets the minimum length of the edge of the mapFrame polygon in page units.</p>


```csharp
public double EdgeMinimumLength { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the grid or graticule is visible.</p>


```csharp
public bool IsVisible { get; set; }
```
### MapGridEdges

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets the map grid edges.</p>


```csharp
public CIMMapGridEdge[] MapGridEdges { get; set; }
```
### MaxInteriorAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets the maximum value of the interior angle that determines the edge of the mapFrame polygon.
The angle is defined in degrees.</p>


```csharp
public double MaxInteriorAngle { get; set; }
```
### MaxScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets the maximum scale.</p>


```csharp
public double MaxScale { get; set; }
```
### MinScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets the minimum scale.</p>


```csharp
public double MinScale { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets the name of the Grid or Graticule.</p>


```csharp
public string Name { get; set; }
```
### NeatlineSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Gets or sets the neat line symbol of the Grid or Graticule.</p>


```csharp
public CIMSymbolReference NeatlineSymbol { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMMapGrid.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


