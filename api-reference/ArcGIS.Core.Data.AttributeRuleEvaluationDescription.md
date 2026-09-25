# AttributeRuleEvaluationDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Specifies how an evaluation for validation rules and/or batch calculation rules should be executed via a validation service.</p>


## Object Signature

```csharp
public sealed class AttributeRuleEvaluationDescription
```


## Members

### AttributeRuleEvaluationDescription(AttributeRuleType, VersionEvaluationScope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>AttributeRuleEvaluationDescription</code> class.</p>


```csharp
public AttributeRuleEvaluationDescription(AttributeRuleType attributeRuleType, VersionEvaluationScope versionEvaluationScope)
```
### AttributeRuleEvaluationDescription(AttributeRuleType, VersionEvaluationScope, Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>AttributeRuleEvaluationDescription</code> class.</p>


```csharp
public AttributeRuleEvaluationDescription(AttributeRuleType attributeRuleType, VersionEvaluationScope versionEvaluationScope, Envelope extent)
```
### AttributeRuleEvaluationDescription(AttributeRuleType, Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>AttributeRuleEvaluationDescription</code> class.</p>


```csharp
public AttributeRuleEvaluationDescription(AttributeRuleType attributeRuleType, Envelope extent)
```
### AttributeRuleEvaluationDescription(AttributeRuleType, IEnumerable&lt;Selection&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>AttributeRuleEvaluationDescription</code> class.</p>


```csharp
public AttributeRuleEvaluationDescription(AttributeRuleType attributeRuleType, IEnumerable<Selection> selections)
```
### AttributeRuleType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Gets the type(s) of evaluate operation(s) to be invoked in the validation service.</p>


```csharp
public AttributeRuleType AttributeRuleType { get; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Gets the area of interest to evaluate.  The default value is null.</p>


```csharp
public Envelope Extent { get; }
```
### Selections

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Gets an <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> containing one or more <xref href="ArcGIS.Core.Data.Selection" data-throw-if-not-resolved="false"></xref>s.  The default value is an empty list.</p>


```csharp
public IReadOnlyList<Selection> Selections { get; }
```
### ServiceSynchronizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.ServiceSynchronizationType" data-throw-if-not-resolved="false"></xref> for the evaluate operation. An optional value.  If not set, the default value is <xref href="ArcGIS.Core.Data.ServiceSynchronizationType.Asynchronous" data-throw-if-not-resolved="false"></xref></p>


```csharp
public ServiceSynchronizationType ServiceSynchronizationType { get; set; }
```
### VersionEvaluationScope

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleEvaluationDescription.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.VersionEvaluationScope" data-throw-if-not-resolved="false"></xref> indicating how a version should be evaluated.  The default value is <xref href="ArcGIS.Core.Data.VersionEvaluationScope.EntireVersion" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public VersionEvaluationScope VersionEvaluationScope { get; }
```


