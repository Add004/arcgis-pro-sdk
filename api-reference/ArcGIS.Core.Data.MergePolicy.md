# MergePolicy

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.MergePolicy.yml" sourcestartlinenumber="1">Controls the value of attributes in the new feature.</p>


## Object Signature

```csharp
public enum MergePolicy
```


## Members

### AreaWeighted

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.MergePolicy.yml" sourcestartlinenumber="1">The attribute of the resulting feature is the weighted average of the values of the attributes from the original features.</p>


```csharp
AreaWeighted = 2
```
### DefaultValue

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.MergePolicy.yml" sourcestartlinenumber="1">The attribute of the resulting feature takes on the default value for the attribute of the given feature or subtype.</p>


```csharp
DefaultValue = 3
```
### SumValues

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.MergePolicy.yml" sourcestartlinenumber="1">The attribute of the resulting feature takes on the sum of the values from the original features' attributes.</p>


```csharp
SumValues = 1
```


