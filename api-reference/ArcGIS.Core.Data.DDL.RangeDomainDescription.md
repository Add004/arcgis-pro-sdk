# RangeDomainDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.DDL.html">DDL</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DDL.RangeDomainDescription.yml" sourcestartlinenumber="1">Represents a mechanism to create a <xref href="ArcGIS.Core.Data.RangeDomain" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class RangeDomainDescription : DomainDescription
```


## Members

### RangeDomainDescription(RangeDomainToken)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RangeDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RangeDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RangeDomainDescription(RangeDomainToken rangeDomainToken)
```
### RangeDomainDescription(RangeDomain)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RangeDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RangeDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RangeDomainDescription(RangeDomain rangeDomain)
```
### RangeDomainDescription(string, FieldType, object, object)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RangeDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RangeDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RangeDomainDescription(string name, FieldType fieldType, object minValue, object maxValue)
```
### RangeDomainDescription(string, RangeDomain)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DDL.RangeDomainDescription.yml" sourcestartlinenumber="1">Creates a description object of the <xref href="ArcGIS.Core.Data.RangeDomain" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public RangeDomainDescription(string name, RangeDomain rangeDomain)
```
### MaxValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RangeDomainDescription.yml" sourcestartlinenumber="1">The maximum value of the range.</p>


```csharp
public object MaxValue { get; set; }
```
### MinValue

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DDL.RangeDomainDescription.yml" sourcestartlinenumber="1">The minimum value of the range.</p>


```csharp
public object MinValue { get; set; }
```


