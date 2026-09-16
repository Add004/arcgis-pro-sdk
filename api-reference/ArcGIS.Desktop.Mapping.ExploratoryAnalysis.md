# ExploratoryAnalysis

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ExploratoryAnalysis.yml" sourcestartlinenumber="1">The abstract base class for all Exploratory Analysis types.  Used to create a manage a common collection of all Exploratory Analysis objects.</p>


## Object Signature

```csharp
public abstract class ExploratoryAnalysis
```

## Remarks

<p>3D Exploratory Analysis is a suite of interactive tools for performing various forms of quick investigation 
    by interactively creating graphics and editing analysis parameters on-the-fly.  Real-time visual feedback is provided
    in the scene.</p>
<p>A collection of existing Exploratory Analysis objects can be queried with <xref href="ArcGIS.Desktop.Mapping.MapView.GetExploratoryAnalysisCollection" data-throw-if-not-resolved="false"></xref> 
    which returns a collection of ExploratoryAnalysisBase objects.  You can cast each object to its appropriate subclass to work with it.</p>


## Members

### ExploratoryAnalysis()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.ExploratoryAnalysis.yml" sourcestartlinenumber="1">Base class constructor</p>


```csharp
protected ExploratoryAnalysis()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ExploratoryAnalysis.yml" sourcestartlinenumber="1">Identifier for the exploratory analysis object within its current MapView.</p>
<p>
The ID is only unique to the map view that it was added to.  For
this reason, the same instance should not be added to more than
one MapView.  Use the subclass's copy constructor for that.
</p>


```csharp
public int ID { get; }
```
### MapView

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ExploratoryAnalysis.yml" sourcestartlinenumber="1">The current MapView that this exploratory analysis object is in.</p>


```csharp
public MapView MapView { get; }
```


