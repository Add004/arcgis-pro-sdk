# CodedValueDomain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Attributes.html">Attributes</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.CodedValueDomain.yml" sourcestartlinenumber="1">Represents a coded value domain.</p>


## Object Signature

```csharp
public sealed class CodedValueDomain : Domain
```

## Remarks

<p>A coded value domain can apply to any type of attribute—text, numeric, date, and so on. 
    Coded value domains specify a valid set of values for an attribute.</p>


## Members

### CodedValues

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.CodedValueDomain.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Desktop.Editing.Attributes.CodedValueDomain.CodedValue?text=Coded+Values" data-throw-if-not-resolved="false"></xref> for this domain.</p>


```csharp
public IEnumerable<CodedValueDomain.CodedValue> CodedValues { get; }
```
### IsMemberOf(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.CodedValueDomain.yml" sourcestartlinenumber="1">Determines if the given object belongs to this Domain.</p>


```csharp
public override bool IsMemberOf(object value)
```
### this[object]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.CodedValueDomain.yml" sourcestartlinenumber="1">Looks up a CodedValue's name by its value.</p>


```csharp
public string this[object value] { get; }
```
### this[string]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.CodedValueDomain.yml" sourcestartlinenumber="1">Looks up a CodedValue by Name.</p>


```csharp
public object this[string name] { get; }
```


