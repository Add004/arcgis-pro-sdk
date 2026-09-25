# Field

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Represents a column in a table.</p>


## Object Signature

```csharp
public class Field : CoreObjectsBase, IDisposable
```

## Remarks

<p>
    Provides access to members that return information about the field.  The field object represents a column in a table. A field has many 
    properties, the most obvious ones being its name and its data type.  The <xref href="ArcGIS.Core.Data.FieldType" data-throw-if-not-resolved="false"></xref> enumeration lists the 
    possible datatypes.
    </p>
<p>
    Some field names, although valid in ArcGIS, conflict with internal properties used by Enterprise geodatabases for storing geometries. 
    A table created using one of these field names will have the field name qualified in the table to avoid potential ambiguity. 
    A qualified field name is returned as "USERNAME.TABLENAME.FIELDNAME" by Oracle and "DATABASE.USERNAME.TABLENAME.FIELDNAME" by SQL Server and PostgreSQL. 
    </p>
<p>
    The following 14 field names will be qualified in Enterprise geodatabases: FID, AREA, LEN, POINTS, NUMOFPTS, ENTITY, EMINX, EMINY, EMAXX, EMAXY, EMINZ, EMAXZ, MIN_MEASURE and MAX_MEASURE.
    The <xref href="ArcGIS.Core.Data.Field.Name" data-throw-if-not-resolved="false"></xref> property of these fields will be qualified when retrieved from the datasets fields collection. 
    Attempting to retrieve the index of a qualified field using <xref href="ArcGIS.Core.Data.Row.FindField(System.String)" data-throw-if-not-resolved="false"></xref> requires the developer to qualify the field name.
    </p>


## Members

### AliasName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets the alias name of the field.</p>


```csharp
public string AliasName { get; }
```
### FieldType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.FieldType" data-throw-if-not-resolved="false"></xref> of the field.</p>


```csharp
public FieldType FieldType { get; }
```
### GetDefaultValue(Subtype)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets the field's default value at the table level if <code class="paramref">subtype</code> is not set.  Otherwise, gets the field's default value for the specific <code class="paramref">subtype</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetDefaultValue(Subtype subtype = null)
```
### GetDomain(Subtype)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets the field's <xref href="ArcGIS.Core.Data.Domain" data-throw-if-not-resolved="false"></xref> at the table level if <code class="paramref">subtype</code> is not set.  Otherwise, gets the field's domain for the specific <code class="paramref">subtype</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Domain GetDomain(Subtype subtype = null)
```
### HasDefaultValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating whether this field has a default value.</p>


```csharp
public bool HasDefaultValue { get; }
```
### IsDomainFixed

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating whether this field's domain is fixed by the system and cannot be unassigned.</p>


```csharp
public bool IsDomainFixed { get; }
```
### IsEditable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating whether this field should be treated as read only by supported clients.</p>


```csharp
public bool IsEditable { get; }
```
### IsNullable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating whether this field can contain null values.</p>


```csharp
public bool IsNullable { get; }
```
### IsRequired

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating whether this is a required field.</p>


```csharp
public bool IsRequired { get; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating the maximum length in bytes for values described by the field.</p>


```csharp
public int Length { get; }
```
### ModelName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets the model name of the field.</p>


```csharp
public string ModelName { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets the name of the field.</p>


```csharp
public string Name { get; }
```
### Precision

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating the precision for field values.</p>


```csharp
public int Precision { get; }
```
### Scale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Field.yml" sourcestartlinenumber="1">Gets a value indicating the scale for field values.</p>


```csharp
public int Scale { get; }
```


