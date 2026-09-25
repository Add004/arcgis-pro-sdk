# KGMergePropertiesWithMissingData

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.KGMergePropertiesWithMissingData.yml" sourcestartlinenumber="1">Specifies the behavior when merge properties have missing data.</p>


## Object Signature

```csharp
public enum KGMergePropertiesWithMissingData
```


## Members

### CreateAndMerge

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGMergePropertiesWithMissingData.yml" sourcestartlinenumber="1">Create or merge the item using the merge properties with missing data.</p>


```csharp
CreateAndMerge = 2
```
### CreateButDoNotMerge

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGMergePropertiesWithMissingData.yml" sourcestartlinenumber="1">Create the item using the merge properties with missing data, but do not merge with it.</p>


```csharp
CreateButDoNotMerge = 1
```
### DoNotCreateOrMerge

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGMergePropertiesWithMissingData.yml" sourcestartlinenumber="1">Do not create or merge the item if any merge property has missing data.</p>


```csharp
DoNotCreateOrMerge = 0
```


