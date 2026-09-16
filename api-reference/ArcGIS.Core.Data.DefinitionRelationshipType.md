# DefinitionRelationshipType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DefinitionRelationshipType.yml" sourcestartlinenumber="1">Specifies the relationship between dataset definitions.</p>


## Object Signature

```csharp
public enum DefinitionRelationshipType
```


## Members

### DatasetInFeatureDataset

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DefinitionRelationshipType.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> contained within an <xref href="ArcGIS.Core.Data.FeatureDataset" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
DatasetInFeatureDataset = 0
```
### DatasetsRelatedThrough

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DefinitionRelationshipType.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.Dataset" data-throw-if-not-resolved="false"></xref> related through an <xref href="ArcGIS.Core.Data.RelationshipClass" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.AttributedRelationshipClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
DatasetsRelatedThrough = 2
```
### FeatureClassInUtilityNetwork

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DefinitionRelationshipType.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> participating in an <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
FeatureClassInUtilityNetwork = 16
```
### TableInUtilityNetwork

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DefinitionRelationshipType.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> participating in an <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetwork" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
TableInUtilityNetwork = 17
```


