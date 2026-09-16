# SymbolExtensionMethods

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Extension methods for various CIM symbol classes.</p>


## Object Signature

```csharp
public static class SymbolExtensionMethods
```


## Members

### GetAngle(CIMPointSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Gets rotation value of a point symbol.</p>


```csharp
public static double GetAngle(this CIMPointSymbol symbol)
```
### GetColor(CIMSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Gets color of a symbol.</p>


```csharp
public static CIMColor GetColor(this CIMSymbol symbol)
```
### GetOutlineColor(CIMPolygonSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Gets outline color of a polygon symbol.</p>


```csharp
public static CIMColor GetOutlineColor(this CIMPolygonSymbol symbol)
```
### GetSize(CIMSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Gets size of a symbol.</p>


```csharp
public static double GetSize(this CIMSymbol symbol)
```
### HasMixedColor(CIMSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Determines whether a symbol color is in mixed state.</p>


```csharp
public static bool HasMixedColor(this CIMSymbol symbol)
```
### HasMixedOutlineColor(CIMPolygonSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Determines whether a polygon symbol outline color is in mixed state.</p>


```csharp
public static bool HasMixedOutlineColor(this CIMPolygonSymbol symbol)
```
### MakeSymbolReference(CIMSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Makes symbol reference for a symbol.</p>


```csharp
public static CIMSymbolReference MakeSymbolReference(this CIMSymbol symbol)
```
### SetAngle(CIMPointSymbol, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Sets rotation of a point symbol.</p>


```csharp
public static void SetAngle(this CIMPointSymbol symbol, double angle)
```
### SetColor(CIMSymbol, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Sets color of a symbol.</p>


```csharp
public static void SetColor(this CIMSymbol symbol, CIMColor color)
```
### SetOutlineColor(CIMPolygonSymbol, CIMColor)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Sets the outline color of a polygon symbol.</p>


```csharp
public static void SetOutlineColor(this CIMPolygonSymbol symbol, CIMColor color)
```
### SetRealWorldUnits(CIMSymbol, bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Sets whether symbol should be displayed with real world size or with fixed screen size.</p>


```csharp
public static void SetRealWorldUnits(this CIMSymbol symbol, bool realWorldUnits)
```
### SetSize(CIMSymbol, double)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.SymbolExtensionMethods.yml" sourcestartlinenumber="1">Sets size of a symbol.</p>


```csharp
public static void SetSize(this CIMSymbol symbol, double size)
```


