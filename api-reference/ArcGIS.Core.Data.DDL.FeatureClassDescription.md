# FeatureClassDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.FeatureClassDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class FeatureClassDescription : TableDescription
```


## Members

### FeatureClassDescription(FeatureClassToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.FeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureClassDescription(FeatureClassToken featureClassToken)
```
### FeatureClassDescription(FeatureClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.FeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureClassDescription(FeatureClassDefinition featureClassDefinition)
```
### FeatureClassDescription(string, FeatureClassDefinition)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.FeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureClassDescription(string name, FeatureClassDefinition featureClassDefinition)
```
### FeatureClassDescription(string, IEnumerable&lt;FieldDescription&gt;, ShapeDescription)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.FeatureClassDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FeatureClassDescription(string name, IEnumerable<FieldDescription> fieldDescriptions, ShapeDescription shapeDescription)
```
### ShapeDescription

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.FeatureClassDescription.yml" sourcestartlinenumber="1">Represents the shape <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ShapeDescription ShapeDescription { get; }
```


