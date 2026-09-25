# DimensionFeatureClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeatureClass.yml" sourcestartlinenumber="1">Represents a dimension feature class.</p>


## Object Signature

```csharp
public sealed class DimensionFeatureClass : FeatureClass, IDisposable
```


## Members

### CreateRow(RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeatureClass.yml" sourcestartlinenumber="1">Creates a new dimension feature in the feature class with a system assigned object ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public DimensionFeature CreateRow(RowBuffer featureBuffer)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeatureClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClassDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.</p>


```csharp
public DimensionFeatureClassDefinition GetDefinition()
```


