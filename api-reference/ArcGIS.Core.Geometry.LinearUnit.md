# LinearUnit

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Geometry.html">Geometry</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Represents a linear unit of measure used by a <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, or in measurement conversion functions.</p>


## Object Signature

```csharp
public sealed class LinearUnit : Unit
```

## Remarks

<p></p>
<p>The available linear units of measure.</p>
<p></p>
<table>
  <tbody>
    <tr>
      <th>Factory Code</th>
      <th>Unit Name</th>
    </tr>
    <tr>
      <td>9001</td>
      <td>International meter</td>
    </tr>
    <tr>
      <td>9002</td>
      <td>International foot</td>
    </tr>
    <tr>
      <td>9003</td>
      <td>US survey foot</td>
    </tr>
    <tr>
      <td>9005</td>
      <td>Clarke's foot</td>
    </tr>
    <tr>
      <td>9014</td>
      <td>Fathom</td>
    </tr>
    <tr>
      <td>9030</td>
      <td>International nautical mile</td>
    </tr>
    <tr>
      <td>9031</td>
      <td>German legal meter</td>
    </tr>
    <tr>
      <td>9033</td>
      <td>US survey chain</td>
    </tr>
    <tr>
      <td>9034</td>
      <td>US survey link</td>
    </tr>
    <tr>
      <td>9035</td>
      <td>US survey mile</td>
    </tr>
    <tr>
      <td>9036</td>
      <td>Kilometer</td>
    </tr>
    <tr>
      <td>9037</td>
      <td>Yard (Clarke's ratio)</td>
    </tr>
    <tr>
      <td>9038</td>
      <td>Chain (Clarke's ratio)</td>
    </tr>
    <tr>
      <td>9039</td>
      <td>Link (Clarke's ratio)</td>
    </tr>
    <tr>
      <td>9040</td>
      <td>Yard (Sears)</td>
    </tr>
    <tr>
      <td>9041</td>
      <td>Sear's foot</td>
    </tr>
    <tr>
      <td>9042</td>
      <td>Chain (Sears)</td>
    </tr>
    <tr>
      <td>9043</td>
      <td>Link (Sears)</td>
    </tr>
    <tr>
      <td>9050</td>
      <td>Yard (Benoit 1895 A)</td>
    </tr>
    <tr>
      <td>9051</td>
      <td>Foot (Benoit 1895 A)</td>
    </tr>
    <tr>
      <td>9052</td>
      <td>Chain (Benoit 1895 A)</td>
    </tr>
    <tr>
      <td>9053</td>
      <td>Link (Benoit 1895 A)</td>
    </tr>
    <tr>
      <td>9060</td>
      <td>Yard (Benoit 1895 B)</td>
    </tr>
    <tr>
      <td>9061</td>
      <td>Foot (Benoit 1895 B)</td>
    </tr>
    <tr>
      <td>9062</td>
      <td>Chain (Benoit 1895 B)</td>
    </tr>
    <tr>
      <td>9063</td>
      <td>Link (Benoit 1895 B)</td>
    </tr>
    <tr>
      <td>9070</td>
      <td>Foot (1865)</td>
    </tr>
    <tr>
      <td>9080</td>
      <td>Indian geodetic foot</td>
    </tr>
    <tr>
      <td>9081</td>
      <td>Indian foot (1937)</td>
    </tr>
    <tr>
      <td>9082</td>
      <td>Indian foot (1962)</td>
    </tr>
    <tr>
      <td>9083</td>
      <td>Indian foot (1975)</td>
    </tr>
    <tr>
      <td>9084</td>
      <td>Indian yard</td>
    </tr>
    <tr>
      <td>9085</td>
      <td>Indian yard (1937)</td>
    </tr>
    <tr>
      <td>9086</td>
      <td>Indian yard (1962)</td>
    </tr>
    <tr>
      <td>9087</td>
      <td>Indian yard (1975)</td>
    </tr>
    <tr>
      <td>9093</td>
      <td>Statute mile</td>
    </tr>
    <tr>
      <td>9094</td>
      <td>Gold Coast foot</td>
    </tr>
    <tr>
      <td>9095</td>
      <td>British foot (1936)</td>
    </tr>
    <tr>
      <td>9096</td>
      <td>International yard</td>
    </tr>
    <tr>
      <td>109002</td>
      <td>US survey yard</td>
    </tr>
    <tr>
      <td>109003</td>
      <td>International Chain</td>
    </tr>
    <tr>
      <td>109004</td>
      <td>International Link</td>
    </tr>
    <tr>
      <td>109005</td>
      <td>Decimeter</td>
    </tr>
    <tr>
      <td>109006</td>
      <td>Centimeter</td>
    </tr>
    <tr>
      <td>109007</td>
      <td>Millimeter</td>
    </tr>
    <tr>
      <td>109008</td>
      <td>International inch</td>
    </tr>
    <tr>
      <td>109009</td>
      <td>US survey inch</td>
    </tr>
    <tr>
      <td>109010</td>
      <td>International rod</td>
    </tr>
    <tr>
      <td>109011</td>
      <td>US survey rod</td>
    </tr>
    <tr>
      <td>109012</td>
      <td>US nautical mile (pre 1954)</td>
    </tr>
    <tr>
      <td>109013</td>
      <td>UK nautical mile (pre 1970)</td>
    </tr>
    <tr>
      <td>109016</td>
      <td>Point</td>
    </tr>
    <tr>
      <td>109030</td>
      <td>50 kilometer length</td>
    </tr>
    <tr>
      <td>109031</td>
      <td>150 kilometer length</td>
    </tr>
    <tr>
      <td>109406</td>
      <td>US square foot</td>
    </tr>
  </tbody>
</table>
<p></p>


## Members

### Centimeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing centimeters (Factory code = 109006).</p>


```csharp
public static LinearUnit Centimeters { get; }
```
### ConvertFromMeters(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Converts a value in meters to the unit of this instance.</p>


```csharp
public double ConvertFromMeters(double meters)
```
### ConvertTo(double, LinearUnit)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Converts a value in the unit of this instance to the provided linear unit.</p>


```csharp
public double ConvertTo(double inDistance, LinearUnit outUnit)
```
### ConvertToMeters(double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Converts a value in the unit of this instance to meters.</p>


```csharp
public double ConvertToMeters(double distance)
```
### CreateLinearUnit(int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a <xref href="ArcGIS.Core.Geometry.LinearUnit" data-throw-if-not-resolved="false"></xref> instance using a factory code.</p>


```csharp
public static LinearUnit CreateLinearUnit(int factoryCode)
```
### CreateLinearUnit(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Convenience method to create a <xref href="ArcGIS.Core.Geometry.LinearUnit" data-throw-if-not-resolved="false"></xref> instance from well-known text. This method is useful for creating a custom unit.</p>


```csharp
public static LinearUnit CreateLinearUnit(string unitWkt)
```
### CreateLinearUnit(string, double)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Convenience method to quickly create a custom <xref href="ArcGIS.Core.Geometry.LinearUnit" data-throw-if-not-resolved="false"></xref> instance.</p>


```csharp
public static LinearUnit CreateLinearUnit(string name, double conversionFactor)
```
### Decimeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing decimeters (Factory code = 109005).</p>


```csharp
public static LinearUnit Decimeters { get; }
```
### Feet

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing feet (Factory code = 9002).</p>


```csharp
public static LinearUnit Feet { get; }
```
### Inches

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing inches (Factory code = 109008).</p>


```csharp
public static LinearUnit Inches { get; }
```
### Kilometers

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing kilometers (Factory code = 9036).</p>


```csharp
public static LinearUnit Kilometers { get; }
```
### Meters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing meters (Factory code = 9001).</p>


```csharp
public static LinearUnit Meters { get; }
```
### MetersPerUnit

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets the meters per unit.</p>


```csharp
public double MetersPerUnit { get; }
```
### Miles

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing miles (Factory code = 9093).</p>


```csharp
public static LinearUnit Miles { get; }
```
### Millimeters

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing millimeters (Factory code = 109007).</p>


```csharp
public static LinearUnit Millimeters { get; }
```
### NauticalMiles

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing international nautical miles (Factory code = 9030).</p>


```csharp
public static LinearUnit NauticalMiles { get; }
```
### Points

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing Desktop publishing points (Factory code = 109016).
A point = 1/72 of an international inch.</p>


```csharp
public static LinearUnit Points { get; }
```
### Yards

- Kind: property

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Gets a linear unit representing yards (Factory code = 9096).</p>


```csharp
public static LinearUnit Yards { get; }
```


