# AnnotationFeatureClassDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of an <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AnnotationFeatureClassDefinition : FeatureClassDefinition, IDisposable
```


## Members

### AreSymbolOverridesAllowed()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the value of whether symbol overrides are allowed.</p>


```csharp
public bool AreSymbolOverridesAllowed()
```
### GetGeneralPlacementProperties()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the general placement properties of the annotation</p>


```csharp
public CIMGeneralPlacementProperties GetGeneralPlacementProperties()
```
### GetLabelClassCollection()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the collection of label classes for the annotation</p>


```csharp
public IReadOnlyList<CIMLabelClass> GetLabelClassCollection()
```
### GetReferenceScale()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the value for the reference scale of the annotation.
This method mush be called on the MCT. Use QueuedTask.Run</p>


```csharp
public double GetReferenceScale()
```
### GetReferenceScaleUnits()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the unit that the reference scale is measured in.</p>


```csharp
public Unit GetReferenceScaleUnits()
```
### GetSymbolCollection()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">The symbol collection for the annotation.</p>


```csharp
public IReadOnlyList<CIMSymbolIdentifier> GetSymbolCollection()
```
### GetVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the version of the annotation</p>


```csharp
public short GetVersion()
```
### IsAutoCreate()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets whether annotation is to be automatically created when a feature is created.</p>


```csharp
public bool IsAutoCreate()
```
### IsSymbolIDRequired()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets the value of whether the annotation requires a symbol id.</p>


```csharp
public bool IsSymbolIDRequired()
```
### IsUpdatedOnShapeChange()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Mapping.AnnotationFeatureClassDefinition.yml" sourcestartlinenumber="1">Gets whether the annotation updates when the feature's shape changes.</p>


```csharp
public bool IsUpdatedOnShapeChange()
```


