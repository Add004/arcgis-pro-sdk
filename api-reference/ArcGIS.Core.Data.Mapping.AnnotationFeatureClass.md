# AnnotationFeatureClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClass.yml" sourcestartlinenumber="1">Represents an annotation feature class.</p>


## Object Signature

```csharp
public sealed class AnnotationFeatureClass : FeatureClass, IDisposable
```


## Members

### CreateRow(RowBuffer)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClass.yml" sourcestartlinenumber="1">Creates a new annotation feature in the feature class with a system assigned object ID.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AnnotationFeature CreateRow(RowBuffer featureBuffer)
```
### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClass.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition" data-throw-if-not-resolved="false"></xref> of this dataset.</p>


```csharp
public AnnotationFeatureClassDefinition GetDefinition()
```


