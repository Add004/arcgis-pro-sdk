# PluginField

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.PluginDatastore.html">PluginDatastore</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Represents a column in a plug-in table or feature class.</p>


## Object Signature

```csharp
public sealed class PluginField
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">A plug-in table does not necessarily correspond to a database table on the back end. It can be any data structure or format, but it is <i>presented</i> to ArcGIS as a table.
Similarly, the third-party data structure exposed through the Plugin Datasource does not necessarily contains <i>fields</i>, but they are exposed to ArcGIS in this fashion.</p>


## Members

### PluginField()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginField" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PluginField()
```
### PluginField(string, string, FieldType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Core.Data.PluginDatastore.PluginField" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public PluginField(string name, string aliasName, FieldType fieldType)
```
### AliasName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Gets or sets the alias name of the field.</p>


```csharp
public string AliasName { get; set; }
```
### FieldType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.FieldType" data-throw-if-not-resolved="false"></xref> of the field.</p>


```csharp
public FieldType FieldType { get; set; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Gets or sets the length of a text field.</p>


```csharp
public int Length { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Gets or sets the name of the field.</p>


```csharp
public string Name { get; set; }
```


