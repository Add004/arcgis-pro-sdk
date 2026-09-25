# AnnotationFeatureClassDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AnnotationFeatureClassDescription : FeatureClassDescription
```


## Members

### AnnotationFeatureClassDescription(AnnotationFeatureClassToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AnnotationFeatureClassDescription(AnnotationFeatureClassToken annotationFeatureClassToken)
```
### AnnotationFeatureClassDescription(AnnotationFeatureClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AnnotationFeatureClassDescription(AnnotationFeatureClassDefinition annotationFeatureClassDefinition)
```
### AnnotationFeatureClassDescription(string, AnnotationFeatureClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AnnotationFeatureClassDescription(string name, AnnotationFeatureClassDefinition annotationFeatureClassDefinition)
```
### AnnotationFeatureClassDescription(string, IEnumerable&lt;FieldDescription&gt;, ShapeDescription, CIMGeneralPlacementProperties, IEnumerable&lt;CIMLabelClass&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AnnotationFeatureClassDescription(string name, IEnumerable<FieldDescription> fieldDescriptions, ShapeDescription shapeDescription, CIMGeneralPlacementProperties generalPlacementProperties, IEnumerable<CIMLabelClass> labelClasses)
```
### AnnotationFeatureClassDescription(string, IEnumerable&lt;FieldDescription&gt;, ShapeDescription, CIMGeneralPlacementProperties, IEnumerable&lt;CIMLabelClass&gt;, FeatureClassDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public AnnotationFeatureClassDescription(string name, IEnumerable<FieldDescription> fieldDescriptions, ShapeDescription shapeDescription, CIMGeneralPlacementProperties generalPlacementProperties, IEnumerable<CIMLabelClass> labelClasses, FeatureClassDescription linkedFeatureClassDescription)
```
### GeneralPlacementProperties

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Represents the general placement properties of the annotations.</p>


```csharp
public CIMGeneralPlacementProperties GeneralPlacementProperties { get; }
```
### IsAutoCreate

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Indicates whether or not the annotation will be automatically created when a feature is created.</p>


```csharp
public bool IsAutoCreate { get; set; }
```
### IsSymbolIDRequired

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Indicates whether or not the annotation requires a symbol ID.</p>


```csharp
public bool IsSymbolIDRequired { get; set; }
```
### IsUpdatedOnShapeChange

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">Indicates whether or not the annotation will be updated when the feature's shape changes.</p>


```csharp
public bool IsUpdatedOnShapeChange { get; set; }
```
### LabelClasses

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">The list of <xref href="ArcGIS.Core.CIM.CIMLabelClass" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<CIMLabelClass> LabelClasses { get; }
```
### LabelEngine

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.LabelEngine" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LabelEngine LabelEngine { get; }
```
### LinkedFeatureClassDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">This represents the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> that has a feature linked with a feature in the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureClassDescription LinkedFeatureClassDescription { get; }
```
### MapUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">The units that the reference scale is measured in.</p>


```csharp
public Unit MapUnits { get; set; }
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">The reference scale of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.
This value must be greater than zero.</p>


```csharp
public double ReferenceScale { get; set; }
```
### Symbols

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.AnnotationFeatureClassDescription.yml" sourcestartlinenumber="1">The list of annotation symbols of the <xref href="ArcGIS.Core.Data.Mapping.AnnotationFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public List<CIMSymbolIdentifier> Symbols { get; }
```


