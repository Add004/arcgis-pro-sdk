# CodedValueDomainDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.CodedValueDomainDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.CodedValueDomain" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class CodedValueDomainDescription : DomainDescription
```


## Members

### CodedValueDomainDescription(CodedValueDomain)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.CodedValueDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.CodedValueDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CodedValueDomainDescription(CodedValueDomain codedValueDomain)
```
### CodedValueDomainDescription(CodedValueDomainToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.CodedValueDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.CodedValueDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CodedValueDomainDescription(CodedValueDomainToken codedValueDomainToken)
```
### CodedValueDomainDescription(string, CodedValueDomain)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.CodedValueDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.CodedValueDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CodedValueDomainDescription(string name, CodedValueDomain codedValueDomain)
```
### CodedValueDomainDescription(string, FieldType, SortedList&lt;object, string&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.CodedValueDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.CodedValueDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public CodedValueDomainDescription(string name, FieldType fieldType, SortedList<object, string> codedValuePairs)
```
### CodedValuePairs

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.CodedValueDomainDescription.yml" sourcestartlinenumber="1">Returns the <xref href="System.Collections.Generic.SortedList%602" data-throw-if-not-resolved="false"></xref> of coded value pairs.</p>


```csharp
public SortedList<object, string> CodedValuePairs { get; }
```


