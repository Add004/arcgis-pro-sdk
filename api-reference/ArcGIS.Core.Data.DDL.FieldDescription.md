# FieldDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class FieldDescription : Description
```


## Members

### FieldDescription(Field)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FieldDescription(Field field)
```
### FieldDescription(string, Field)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FieldDescription(string name, Field field)
```
### FieldDescription(string, FieldType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FieldDescription(string name, FieldType fieldType)
```
### AliasName

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">The alias name of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public string AliasName { get; set; }
```
### CreateDomainField(string, DomainDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a field description for a <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> with a specified <xref href="ArcGIS.Core.Data.DDL.DomainDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static FieldDescription CreateDomainField(string name, DomainDescription domainDescription)
```
### CreateGlobalIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a field description for a Global ID <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static FieldDescription CreateGlobalIDField()
```
### CreateIntegerField(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a field description for an integer <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static FieldDescription CreateIntegerField(string name)
```
### CreateObjectIDField()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a field description for an Object ID <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static FieldDescription CreateObjectIDField()
```
### CreateStringField(string, int)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Creates a field description for a string <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public static FieldDescription CreateStringField(string name, int length)
```
### FieldType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">The <xref href="ArcGIS.Core.Data.FieldType" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public FieldType FieldType { get; }
```
### GetDefaultValue(int?)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Gets the default value of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> at the table level if <code class="paramref">subtypeCode</code> is not specified.
Otherwise, gets the default value for the specific subtype code.</p>


```csharp
public object GetDefaultValue(int? subtypeCode = null)
```
### GetDomainDescription(int?)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Gets the associated <xref href="ArcGIS.Core.Data.DDL.DomainDescription" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> at the table
level if <code class="paramref">subtypeCode</code> is not specified.
Otherwise, gets the DomainDescription for the specific subtype code.</p>


```csharp
public DomainDescription GetDomainDescription(int? subtypeCode = null)
```
### IsNullable

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Indicates if the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> can contain null values.</p>


```csharp
public bool IsNullable { get; set; }
```
### Length

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">The length of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int Length { get; set; }
```
### Precision

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">The precision value of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int Precision { get; set; }
```
### Scale

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">The scale of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int Scale { get; set; }
```
### SetDefaultFieldProperties(FieldType)

- Kind: method


```csharp
protected void SetDefaultFieldProperties(FieldType fieldType)
```
### SetDefaultValue(object, int?)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Sets the default value of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> at the table level if <code class="paramref">subtypeCode</code> is not specified.
Otherwise, sets the default value for the specific subtype code.</p>


```csharp
public void SetDefaultValue(object defaultValue, int? subtypeCode = null)
```
### SetDomainDescription(DomainDescription, int?)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.DDL.FieldDescription.yml" sourcestartlinenumber="1">Sets the associated <xref href="ArcGIS.Core.Data.DDL.DomainDescription" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Core.Data.Field" data-throw-if-not-resolved="false"></xref> at the table
level if <code class="paramref">subtypeCode</code> is not specified.
Otherwise, sets the DomainDescription for the specific subtype code.</p>


```csharp
public void SetDomainDescription(DomainDescription domainDescription, int? subtypeCode = null)
```


