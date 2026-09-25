# AttributeRuleManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleManager.yml" sourcestartlinenumber="1">This class provides basic functionality to manage attribute rules on behalf of a geodatabase.</p>


## Object Signature

```csharp
public sealed class AttributeRuleManager : CoreObjectsBase, IDisposable
```


## Members

### CreateAttributeRuleError(Row)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleManager.yml" sourcestartlinenumber="1">Creates a value object representation of an error from a <xref href="ArcGIS.Core.Data.ValidationErrorType" data-throw-if-not-resolved="false"></xref> validation error system table.</p>


```csharp
public AttributeRuleError CreateAttributeRuleError(Row errorFeature)
```
### Evaluate(AttributeRuleEvaluationDescription)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleManager.yml" sourcestartlinenumber="1">Evaluates all the applicable tables and feature classes in this geodatabase using the operation(s) specified by
<code class="paramref">description</code> in the validation service.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributeRuleEvaluationResult Evaluate(AttributeRuleEvaluationDescription description)
```
### GetErrorTable(ValidationErrorType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleManager.yml" sourcestartlinenumber="1">Opens the validation error system table specified by <code class="paramref">validationErrorType</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Table GetErrorTable(ValidationErrorType validationErrorType)
```
### IsEvaluationSupported()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleManager.yml" sourcestartlinenumber="1">Gets a value indicating whether this geodatabase supports evaluation for validation rules or batch calculation rules.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsEvaluationSupported()
```
### UpdateErrors(IEnumerable&lt;AttributeRuleError&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleManager.yml" sourcestartlinenumber="1">Updates the validation error system tables specified by <code class="paramref">validationErrors</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public void UpdateErrors(IEnumerable<AttributeRuleError> validationErrors)
```


