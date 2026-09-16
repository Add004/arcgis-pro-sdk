# SortDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.SortDescription.yml" sourcestartlinenumber="1">Specifies a <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> to be used to sort the table or feature class and how it should be used.</p>


## Object Signature

```csharp
public sealed class SortDescription
```


## Members

### SortDescription(Field)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.SortDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>SortDescription</code> class.</p>


```csharp
public SortDescription(Field field)
```
### CaseSensitivity

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.SortDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.CaseSensitivity" data-throw-if-not-resolved="false"></xref> for the sort operation.
This property is ignored for non-text field types.
The default value is <xref href="ArcGIS.Core.Data.CaseSensitivity.Insensitive" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CaseSensitivity CaseSensitivity { get; set; }
```
### Field

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.SortDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> whose values need to be sorted.</p>


```csharp
public Field Field { get; }
```
### SortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.SortDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.SortOrder" data-throw-if-not-resolved="false"></xref> for the sort operation.<br>
The default value is <xref href="ArcGIS.Core.Data.SortOrder.Ascending" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SortOrder SortOrder { get; set; }
```


