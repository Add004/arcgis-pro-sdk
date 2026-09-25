# FieldDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Represents a field with updatable properties.</p>


## Object Signature

```csharp
public class FieldDescription
```


## Members

### FieldDescription()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Desktop.Mapping.FieldDescription?text=FieldDescription" data-throw-if-not-resolved="false"></xref> class.</p>


```csharp
public FieldDescription()
```
### Alias

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Gets or sets the alias of a field.</p>


```csharp
public string Alias { get; set; }
```
### IsHighlighted

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Gets or sets whether a field is highlighted.</p>


```csharp
public bool IsHighlighted { get; set; }
```
### IsReadOnly

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Gets or sets whether a field is read-only - values in this field cannot be modified.</p>


```csharp
public bool IsReadOnly { get; set; }
```
### IsVisible

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Gets or sets whether a field is visible.
When a field is invisible, result of a
<xref href="ArcGIS.Desktop.Mapping.IDisplayTable.Search(ArcGIS.Core.Data.QueryFilter%2cArcGIS.Desktop.Mapping.TimeRange%2cArcGIS.Desktop.Mapping.RangeExtent%2cArcGIS.Core.CIM.CIMFloorFilterSettings)?text=%0a++++++++++++Search" data-throw-if-not-resolved="false"></xref> method will not include values from this field and the field will not appear in many UI list.</p>


```csharp
public bool IsVisible { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Gets the name of a field.</p>


```csharp
public string Name { get; }
```
### NumberFormat

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Gets or sets numeric format to display values for a field..</p>


```csharp
public CIMNumberFormat NumberFormat { get; set; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.FieldDescription.yml" sourcestartlinenumber="1">Gets the type of a field.</p>


```csharp
public FieldType Type { get; }
```


