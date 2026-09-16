# RelatedPropertyTable

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.RelatedPropertyTable.yml" sourcestartlinenumber="1">Job related property table.</p>


## Object Signature

```csharp
public class RelatedPropertyTable
```


## Members

### RelatedPropertyTable()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.RelatedPropertyTable.yml" sourcestartlinenumber="1">Job related property table.</p>


```csharp
public RelatedPropertyTable()
```
### Entries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.RelatedPropertyTable.yml" sourcestartlinenumber="1">Entries in the table. Each entry represents a row in the table.</p>


```csharp
public List<RelatedPropertyEntry> Entries { get; }
```
### FeatureServiceProperties

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.RelatedPropertyTable.yml" sourcestartlinenumber="1">Feature service properties for the table. Only applies to tables created from a feature service.</p>


```csharp
public FeatureServiceProperties FeatureServiceProperties { get; }
```
### TableName

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.RelatedPropertyTable.yml" sourcestartlinenumber="1">Table name.</p>


```csharp
public string TableName { get; }
```


