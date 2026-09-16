# Unit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">A common base class between all units; linear, area, angular, grid.</p>


## Object Signature

```csharp
public abstract class Unit
```


## Members

### ConversionFactor

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Gets the conversion factor of the unit.</p>


```csharp
public virtual double ConversionFactor { get; }
```
### CreateFromJson(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Creates a unit from a JSON string.</p>


```csharp
public static Unit CreateFromJson(string jsonString)
```
### FactoryCode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Gets the well-known ID of the unit. If the unit is a custom unit, then the factory code will be 0.</p>


```csharp
public int FactoryCode { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Gets the name of the unit.</p>


```csharp
public string Name { get; }
```
### ToJson()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Gets the JSON representation of the unit in terms of the WKID. A custom unit has WKID = 0.</p>


```csharp
public string ToJson()
```
### ToString()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Gets a <xref href="System.String" data-throw-if-not-resolved="false"></xref> that represents this unit.   Returns the <xref href="ArcGIS.Core.Geometry.Unit.Name" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override string ToString()
```
### UnitType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Gets the type of unit.</p>


```csharp
public virtual UnitType UnitType { get; }
```
### Wkt

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">Gets the well-known text of the unit.</p>


```csharp
public string Wkt { get; }
```


