# MultipleLabelLegendClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.MultipleLabelLegendClass.yml" sourcestartlinenumber="1">Represents a symbol legend class item with several Labels.</p>


## Object Signature

```csharp
public class MultipleLabelLegendClass : LegendClass
```


## Members

### LabelPositions

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MultipleLabelLegendClass.yml" sourcestartlinenumber="1">Get the positions of the labels from the top in relation to the
associated patch for the symbol. The top of the patch would be 0.0,
the bottom of the patch would be 1.0.</p>


```csharp
public List<double> LabelPositions { get; }
```
### Labels

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.MultipleLabelLegendClass.yml" sourcestartlinenumber="1">Gets the labels associated with the legend class.</p>


```csharp
public List<string> Labels { get; }
```


