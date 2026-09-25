# SymbolSearcherSearchCompletedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchCompletedEventArgs.yml" sourcestartlinenumber="1">Passed as the event parameter in the StyleSearchCompleted event for the SymbolSearcherControl.</p>


## Object Signature

```csharp
public class SymbolSearcherSearchCompletedEventArgs : EventArgs
```


## Members

### ResultType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the style type of the results.</p>


```csharp
public StyleItemType ResultType { get; }
```
### Results

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.SymbolSearcherSearchCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the search results.</p>


```csharp
public IReadOnlyList<StyleItem> Results { get; }
```


