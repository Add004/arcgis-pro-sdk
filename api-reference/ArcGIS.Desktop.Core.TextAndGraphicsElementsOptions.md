# TextAndGraphicsElementsOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Gets and sets the application options for default font and
graphic element symbology.</p>


## Object Signature

```csharp
public class TextAndGraphicsElementsOptions
```


## Members

### GetAvailableFonts()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Gets the list of available fonts in the application for the Pro session.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<(string fontName, List<string> fontStyles)> GetAvailableFonts()
```
### GetDefaultFont()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Gets the application default font family name and style.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public (string fontName, string styleName) GetDefaultFont()
```
### GetDefaultLineSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Gets the application default line symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMLineSymbol GetDefaultLineSymbol()
```
### GetDefaultPointSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Gets the application default point symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPointSymbol GetDefaultPointSymbol()
```
### GetDefaultPolygonSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Gets the application default polygon symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMPolygonSymbol GetDefaultPolygonSymbol()
```
### GetDefaultTextSymbol()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Gets the application default text symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public CIMTextSymbol GetDefaultTextSymbol()
```
### SetDefaultFont(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Sets the application default font family name and style.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultFont(string familyName)
```
### SetDefaultFont(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Sets the application default font family name and style.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultFont(string familyName, string styleName)
```
### SetDefaultLineSymbol(CIMLineSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Sets the application default line symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultLineSymbol(CIMLineSymbol lineSymbol)
```
### SetDefaultPointSymbol(CIMPointSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Sets the application default point symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultPointSymbol(CIMPointSymbol pointSymbol)
```
### SetDefaultPolygonSymbol(CIMPolygonSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Sets the application default polygon symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultPolygonSymbol(CIMPolygonSymbol polygonSymbol)
```
### SetDefaultTextSymbol(CIMTextSymbol)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.TextAndGraphicsElementsOptions.yml" sourcestartlinenumber="1">Sets the application default text symbol.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void SetDefaultTextSymbol(CIMTextSymbol textSymbol)
```


