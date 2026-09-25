# ENCSubTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCSubTable.yml" sourcestartlinenumber="1">Represents a subtable within an ENC layer.</p>


## Object Signature

```csharp
public sealed class ENCSubTable : StandaloneTable, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCSubTable.yml" sourcestartlinenumber="1">Gets the table's definition which is null for ENC subtables.</p>


```csharp
public override CIMStandaloneTable GetDefinition()
```
### SupportsMetadata

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.ENCSubTable.yml" sourcestartlinenumber="1">Gets whether the ENCSubTable supports metadata</p>


```csharp
public override bool SupportsMetadata { get; }
```


