# SymbolSearcherSearchOutputOptions

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchOutputOptions.yml" sourcestartlinenumber="1">Specify default search output options for the returned
StyleItems (from a search).</p>


## Object Signature

```csharp
public class SymbolSearcherSearchOutputOptions
```


## Members

### SymbolSearcherSearchOutputOptions()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchOutputOptions.yml" sourcestartlinenumber="1">Initializes an empty instance of the <xref href="ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchOutputOptions" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public SymbolSearcherSearchOutputOptions()
```
### DefaultPatchTypes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchOutputOptions.yml" sourcestartlinenumber="1">Gets and sets the default patch styles for symbolstyleitems.</p>


```csharp
public Dictionary<StyleItemType, SymbolPatchType> DefaultPatchTypes { get; set; }
```
### FitSizeForPointSymbol

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchOutputOptions.yml" sourcestartlinenumber="1">Gets and sets whether output Point SymbolStyleItems will be
&quot;set&quot; to fill their preview image patch.</p>


```csharp
public bool FitSizeForPointSymbol { get; set; }
```


