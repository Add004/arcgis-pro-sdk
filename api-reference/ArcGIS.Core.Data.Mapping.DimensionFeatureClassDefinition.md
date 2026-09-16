# DimensionFeatureClassDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeatureClassDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of a <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class DimensionFeatureClassDefinition : FeatureClassDefinition, IDisposable
```


## Members

### GetDimensionStyles()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the dimension styles for the dimension feature class.
This method mush be called on the MCT. Use QueuedTask.Run</p>


```csharp
public IReadOnlyList<CIMDimensionStyle> GetDimensionStyles()
```
### GetReferenceScale()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the value for the reference scale of the dimension feature class.
This method mush be called on the MCT. Use QueuedTask.Run</p>


```csharp
public double GetReferenceScale()
```
### GetReferenceScaleUnits()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.DimensionFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the value for the reference scale unit of the dimension feature class.
This method mush be called on the MCT. Use QueuedTask.Run</p>


```csharp
public Unit GetReferenceScaleUnits()
```


