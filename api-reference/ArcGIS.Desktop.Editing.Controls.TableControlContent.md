# TableControlContent

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.TableControlContent.yml" sourcestartlinenumber="1">Defines the content source for the TableControl.</p>


## Object Signature

```csharp
public sealed class TableControlContent : IInternalTableControlContent
```


## Members

### FieldOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.TableControlContent.yml" sourcestartlinenumber="1">Gets and sets a comma separated list indicating the display order of fields.
This property is only supported for Item sources.</p>


```csharp
public string FieldOrder { get; set; }
```
### SqlQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.TableControlContent.yml" sourcestartlinenumber="1">Gets and sets an SQL query that will be applied to the table attributes.</p>


```csharp
public string SqlQuery { get; set; }
```
### ViewMode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.TableControlContent.yml" sourcestartlinenumber="1">Gets and sets initial view mode of the table.</p>


```csharp
public TableViewMode ViewMode { get; set; }
```
### VisibleFields

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Controls.TableControlContent.yml" sourcestartlinenumber="1">Gets and sets a comma separated list of visible field names.
This property is only supported for Item sources.</p>


```csharp
public string VisibleFields { get; set; }
```


