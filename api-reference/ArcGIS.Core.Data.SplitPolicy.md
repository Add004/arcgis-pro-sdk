# SplitPolicy

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.SplitPolicy.yml" sourcestartlinenumber="1">Controls the value of the attribute in the output features.</p>


## Object Signature

```csharp
public enum SplitPolicy
```


## Members

### DefaultValue

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SplitPolicy.yml" sourcestartlinenumber="1">The attributes of the resulting features take on the default value for the attribute of the given feature class or subtype.</p>


```csharp
DefaultValue = 3
```
### Duplicate

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SplitPolicy.yml" sourcestartlinenumber="1">The attributes of the resulting features take on a copy of the original object's attribute value.</p>


```csharp
Duplicate = 2
```
### GeometryRatio

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.SplitPolicy.yml" sourcestartlinenumber="1">The attributes of the resulting features are a ratio of the original feature's value.</p>


```csharp
GeometryRatio = 1
```


