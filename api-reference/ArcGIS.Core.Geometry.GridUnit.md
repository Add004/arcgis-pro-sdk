# GridUnit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.GridUnit.yml" sourcestartlinenumber="1">Represents a grid unit for a geographic location.</p>


## Object Signature

```csharp
public sealed class GridUnit : Unit
```

## Remarks

<p></p>
<p>The available grid units.</p>
<p></p>
<table>
  <tbody>
    <tr>
      <th>Factory Code</th>
      <th>Unit Name</th>
    </tr>
    <tr>
      <td>909000</td>
      <td>MGRS (Military Grid Reference System)</td>
    </tr>
    <tr>
      <td>909001</td>
      <td>USNG (United States National Grid)</td>
    </tr>
    <tr>
      <td>909002</td>
      <td>UTM (Universal Transverse Mercator)</td>
    </tr>
  </tbody>
</table>


## Members

### CreateGridUnit(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GridUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a <xref href="ArcGIS.Core.Geometry.GridUnit" data-throw-if-not-resolved="false"></xref> instance using a factory code.</p>


```csharp
public static GridUnit CreateGridUnit(int factoryCode)
```
### CreateGridUnit(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.GridUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a <xref href="ArcGIS.Core.Geometry.GridUnit" data-throw-if-not-resolved="false"></xref> instance using a name.</p>


```csharp
public static GridUnit CreateGridUnit(string name)
```
### MGRS

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GridUnit.yml" sourcestartlinenumber="1">Gets a grid unit object representing a geographic location in the Military Grid System.</p>


```csharp
public static GridUnit MGRS { get; }
```
### USNG

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GridUnit.yml" sourcestartlinenumber="1">Gets a grid unit object representing a geographic location in the United States National Grid.</p>


```csharp
public static GridUnit USNG { get; }
```
### UTM

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.GridUnit.yml" sourcestartlinenumber="1">Gets a grid unit object representing a geographic location in Universal Transverse Mercator.</p>


```csharp
public static GridUnit UTM { get; }
```


