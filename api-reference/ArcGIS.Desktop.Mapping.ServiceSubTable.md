# ServiceSubTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubTable.yml" sourcestartlinenumber="1">Represents a service sub table within a service layer.</p>


## Object Signature

```csharp
public sealed class ServiceSubTable : StandaloneTable, IMetadataInfo, IMetadataSource, IDisplayTable, ITableDefinitionQueries, IArcadeEvaluatorObject
```


## Members

### GetDefinition()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubTable.yml" sourcestartlinenumber="1">Returns the service sub table's CIM definition.  Returns null.</p>


```csharp
public override CIMStandaloneTable GetDefinition()
```
### SetDefinition(CIMStandaloneTable)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.ServiceSubTable.yml" sourcestartlinenumber="1">Updates the service sub table's CIM definition.  This will throw an <xref href="System.NotSupportedException" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override void SetDefinition(CIMStandaloneTable table)
```


