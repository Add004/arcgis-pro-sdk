# Domain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Attributes.html">Attributes</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Domain.yml" sourcestartlinenumber="1">Represents an abstract base class for a Domain. There are two subclasses <xref href="ArcGIS.Desktop.Editing.Attributes.RangeDomain?text=RangeDomain" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Desktop.Editing.Attributes.CodedValueDomain?text=CodedValueDomain" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class Domain
```

## Remarks

<p>Attribute domains are rules that describe the legal values of a field type, providing a method for 
    enforcing data integrity. Attribute domains are used to constrain the values allowed in any particular attribute for a 
    table or feature class.</p>


## Members

### Description

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Domain.yml" sourcestartlinenumber="1">Gets the description of this Domain.</p>


```csharp
public string Description { get; }
```
### IsMemberOf(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Domain.yml" sourcestartlinenumber="1">An abstract method. Ideally this method will determine if the given object belongs to this Domain.</p>


```csharp
public abstract bool IsMemberOf(object value)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Attributes.Domain.yml" sourcestartlinenumber="1">Gets the name of this Domain.</p>


```csharp
public string Name { get; }
```


