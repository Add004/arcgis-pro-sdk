# QueryBuilderControlProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControlProperties.yml" sourcestartlinenumber="1">Configures the properties to be used to initialize the QueryBuilderControl.</p>


## Object Signature

```csharp
public class QueryBuilderControlProperties
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControlProperties.yml" sourcestartlinenumber="1">To refresh the QueryBuilderControl (eg the map's layers change), provide an updated
QueryBuilderControlProperties.</p>


## Members

### QueryBuilderControlProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControlProperties.yml" sourcestartlinenumber="1">Construct a QueryBuilderControlProperties to configure the QueryBuilderControl.
Use the MapMember and Expression properties to configure the control. The MapMember property is required.</p>


```csharp
public QueryBuilderControlProperties()
```
### AutoValidate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControlProperties.yml" sourcestartlinenumber="1">Gets and sets the auto validation flag in the QueryBuilderControl.</p>


```csharp
public bool AutoValidate { get; set; }
```
### EditClauseMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControlProperties.yml" sourcestartlinenumber="1">Gets and sets the expression mode of the QueryBuilderControl.  Setting EditClauseMode true means that the control displays the expression in clauses;
a value of false displays the expression as a single SQL string.</p>


```csharp
public bool EditClauseMode { get; set; }
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControlProperties.yml" sourcestartlinenumber="1">Gets and sets the query expression in the QueryBuilderControl.</p>


```csharp
public string Expression { get; set; }
```
### MapMember

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControlProperties.yml" sourcestartlinenumber="1">Gets and sets the mapmember to be used in the QueryBuilderControl.</p>


```csharp
public MapMember MapMember { get; set; }
```


