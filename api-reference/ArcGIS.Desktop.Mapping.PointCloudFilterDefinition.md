# PointCloudFilterDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Represents a definition for a point cloud filter.</p>


## Object Signature

```csharp
public sealed class PointCloudFilterDefinition
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">The point cloud filter definition class allows you to define parameters to create a point cloud filter.</p>


## Members

### PointCloudFilterDefinition()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Creates an empty PointCloudFilterDefinition.</p>


```csharp
public PointCloudFilterDefinition()
```
### PointCloudFilterDefinition(List&lt;int&gt;, List&lt;PointCloudReturnType&gt;, List&lt;ClassFlag&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Creates a PointCloudFilterDefinition.</p>


```csharp
public PointCloudFilterDefinition(List<int> classCodes, List<PointCloudReturnType> returnValues = null, List<ClassFlag> classFlags = null)
```
### ClassCodes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Gets or sets the list of classification codes.</p>


```csharp
public List<int> ClassCodes { get; set; }
```
### ClassFlags

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Gets or sets the list of classification flags.</p>


```csharp
public List<ClassFlag> ClassFlags { get; set; }
```
### FromCIM(IEnumerable&lt;CIMPointCloudFilter&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Creates a PointCloudFilterDefinition based on a collection of
<xref href="ArcGIS.Core.CIM.CIMPointCloudFilter" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static PointCloudFilterDefinition FromCIM(IEnumerable<CIMPointCloudFilter> filters)
```
### ReturnValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Gets or sets the list of return values.</p>


```csharp
public List<PointCloudReturnType> ReturnValues { get; set; }
```
### ToCIM()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.PointCloudFilterDefinition.yml" sourcestartlinenumber="1">Creates a list of CIMPointCloudFilters based on the PointCloudFilterDefinition.</p>


```csharp
public List<CIMPointCloudFilter> ToCIM()
```


