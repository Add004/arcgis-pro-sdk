# AttributeRuleError

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleError.yml" sourcestartlinenumber="1">Represents an error from a <xref href="ArcGIS.Core.Data.ValidationErrorType" data-throw-if-not-resolved="false"></xref> validation error system table.</p>


## Object Signature

```csharp
public sealed class AttributeRuleError
```


## Members

### ErrorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleError.yml" sourcestartlinenumber="1">Gets the type of validation error system table from which this instance of AttributeRuleError is created.</p>


```csharp
public ValidationErrorType ErrorType { get; }
```
### IsException

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleError.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether this error should be treated as an exception.</p>


```csharp
public bool IsException { get; set; }
```
### OriginClass

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleError.yml" sourcestartlinenumber="1">Gets the name of the <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref> in which the error occurred.</p>


```csharp
public string OriginClass { get; }
```
### OriginGlobalID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleError.yml" sourcestartlinenumber="1">Gets the global ID of the offending <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in <xref href="ArcGIS.Core.Data.AttributeRuleError.OriginClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public Guid OriginGlobalID { get; }
```
### OriginObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleError.yml" sourcestartlinenumber="1">Gets the object ID of the offending <xref href="ArcGIS.Core.Data.Row" data-throw-if-not-resolved="false"></xref> in <xref href="ArcGIS.Core.Data.AttributeRuleError.OriginClass" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public long OriginObjectID { get; }
```


