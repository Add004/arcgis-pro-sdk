# CIMRouteEventDataConnection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Represents a route event data connection.</p>


## Object Signature

```csharp
public class CIMRouteEventDataConnection : CIMDataConnection, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMRouteEventDataConnection()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Represents a route event data connection.</p>


```csharp
public CIMRouteEventDataConnection()
```
### AddAngleField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether an angle field should be added to the field set.</p>


```csharp
public bool AddAngleField { get; set; }
```
### AddErrorField

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether an error field should be added to the field set.</p>


```csharp
public bool AddErrorField { get; set; }
```
### AngleFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the angle field name.</p>


```csharp
public string AngleFieldName { get; set; }
```
### AsPointFeature

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the point event shape should be output as a multipoint or a point.</p>


```csharp
public bool AsPointFeature { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Creates a deep copy of CIMRouteEventDataConnection.</p>


```csharp
public CIMRouteEventDataConnection Clone()
```
### ComplementAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether 180 degrees should be added to the angle field value.</p>


```csharp
public bool ComplementAngle { get; set; }
```
### ErrorFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the error field name.</p>


```csharp
public string ErrorFieldName { get; set; }
```
### EventMeasureUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the units of the event measure(s).</p>


```csharp
public Unit EventMeasureUnit { get; set; }
```
### EventRouteIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the route identifier field name.</p>


```csharp
public string EventRouteIDFieldName { get; set; }
```
### EventTable

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the data connection for the route events.</p>


```csharp
public CIMDataConnection EventTable { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Reconstructs the CIMRouteEventDataConnection with a specified state from a JSON encoding.</p>


```csharp
public static CIMRouteEventDataConnection FromJson(string json, JsonDeserializationSettings settings = null)
```
### FromMeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the from measure field name.</p>


```csharp
public string FromMeasureFieldName { get; set; }
```
### IsLineEvent

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not this is a line event.</p>


```csharp
public bool IsLineEvent { get; set; }
```
### LateralOffsetFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the lateral offset field name.</p>


```csharp
public string LateralOffsetFieldName { get; set; }
```
### MDirectionOffsetting

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the offset should based on the M direction or the digitized direction.</p>


```csharp
public bool MDirectionOffsetting { get; set; }
```
### NormalAngle

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the angle field should be the normal or the tangent angles.</p>


```csharp
public bool NormalAngle { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RouteFeatureClass

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the data connection for the route feature class.</p>


```csharp
public CIMDataConnection RouteFeatureClass { get; set; }
```
### RouteIDFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the route identifier field of the route feature class.</p>


```csharp
public string RouteIDFieldName { get; set; }
```
### RouteMeasureUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the route measure units.</p>


```csharp
public Unit RouteMeasureUnit { get; set; }
```
### RouteWhereClause

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the where clause that limits the routes that events can be located on.</p>


```csharp
public string RouteWhereClause { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMRouteEventDataConnection and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### ToMeasureFieldName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Gets or sets the to measure field name.</p>


```csharp
public string ToMeasureFieldName { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMRouteEventDataConnection.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


