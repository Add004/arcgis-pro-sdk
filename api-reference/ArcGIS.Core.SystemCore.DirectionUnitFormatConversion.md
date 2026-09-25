# DirectionUnitFormatConversion

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.SystemCore.html">SystemCore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">This is a singleton. Use to provide your unit format conversion needs.</p>


## Object Signature

```csharp
public sealed class DirectionUnitFormatConversion : IDirectionUnitFormatConversion
```


## Members

### ConvertToDouble(double, ConversionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a double to another double from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public double ConvertToDouble(double value, ConversionDefinition definition)
```
### ConvertToDouble(double, ConversionDefinitionEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a double to another double from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public double ConvertToDouble(double value, ConversionDefinitionEx definition)
```
### ConvertToDouble(string, ConversionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a string to a double from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public double ConvertToDouble(string value, ConversionDefinition definition)
```
### ConvertToDouble(string, ConversionDefinitionEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a string to a double from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public double ConvertToDouble(string value, ConversionDefinitionEx definition)
```
### ConvertToString(double, int, ConversionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a double to a string from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public string ConvertToString(double value, int precision, ConversionDefinition definition)
```
### ConvertToString(double, int, ConversionDefinitionEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a double to a string from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public string ConvertToString(double value, int precision, ConversionDefinitionEx definition)
```
### ConvertToString(string, int, ConversionDefinition)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a string to another string from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public string ConvertToString(string value, int precision, ConversionDefinition definition)
```
### ConvertToString(string, int, ConversionDefinitionEx)

- Kind: method

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Converts a string to another string from definition.DirectionTypeIn, definition.DirectionUnitsIn to definition.DirectionTypeOut, definition.DirectionUnitsOut.</p>


```csharp
public string ConvertToString(string value, int precision, ConversionDefinitionEx definition)
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Core.SystemCore.DirectionUnitFormatConversion.yml" sourcestartlinenumber="1">Gets the singleton instance for UnitFormatConversion</p>


```csharp
public static IDirectionUnitFormatConversion Instance { get; }
```


