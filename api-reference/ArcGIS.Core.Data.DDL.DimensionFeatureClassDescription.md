# DimensionFeatureClassDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class DimensionFeatureClassDescription : FeatureClassDescription
```


## Members

### DimensionFeatureClassDescription(DimensionFeatureClassToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DimensionFeatureClassDescription(DimensionFeatureClassToken dimensionFeatureClassToken)
```
### DimensionFeatureClassDescription(DimensionFeatureClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DimensionFeatureClassDescription(DimensionFeatureClassDefinition dimensionFeatureClassDefinition)
```
### DimensionFeatureClassDescription(string, DimensionFeatureClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DimensionFeatureClassDescription(string name, DimensionFeatureClassDefinition dimensionFeatureClassDefinition)
```
### DimensionFeatureClassDescription(string, IEnumerable&lt;FieldDescription&gt;, ShapeDescription, IEnumerable&lt;CIMDimensionStyle&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public DimensionFeatureClassDescription(string name, IEnumerable<FieldDescription> fieldDescriptions, ShapeDescription shapeDescription, IEnumerable<CIMDimensionStyle> dimensionStyles)
```
### DimensionStyles

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">The list of <xref href="ArcGIS.Core.CIM.CIMDimensionStyle" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public IReadOnlyList<CIMDimensionStyle> DimensionStyles { get; }
```
### MapUnits

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">The units that the reference scale is measured in.</p>


```csharp
public Unit MapUnits { get; set; }
```
### ReferenceScale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.DimensionFeatureClassDescription.yml" sourcestartlinenumber="1">The reference scale of the <xref href="ArcGIS.Core.Data.Mapping.DimensionFeatureClass" data-throw-if-not-resolved="false"></xref>.
This value must be greater than zero.</p>


```csharp
public double ReferenceScale { get; set; }
```


