# Attribute.ValidationError

- Type: struct
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Attributes.html">Attributes</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.ValidationError.yml" sourcestartlinenumber="1">A validation error.
See <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute.AddValidate(System.Func%7bSystem.Collections.Generic.IEnumerable%7bArcGIS.Desktop.Editing.Attributes.Attribute.ValidationError%7d%7d)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.Attributes.Attribute.AddValidateAsync(System.Func%7bSystem.Threading.Tasks.Task%7bSystem.Collections.Generic.IEnumerable%7bArcGIS.Desktop.Editing.Attributes.Attribute.ValidationError%7d%7d%7d)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public struct Attribute.ValidationError
```


## Members

### Create(string, Severity)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.ValidationError.yml" sourcestartlinenumber="1">Creates a new ValidationError.</p>


```csharp
public static Attribute.ValidationError Create(string desc, Severity severity)
```
### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.ValidationError.yml" sourcestartlinenumber="1">Gets and sets the description of the error.</p>


```csharp
public string Description { readonly get; set; }
```
### Severity

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Attribute.ValidationError.yml" sourcestartlinenumber="1">Gets and sets the severity of the error (High or Low).</p>


```csharp
public Severity Severity { readonly get; set; }
```


