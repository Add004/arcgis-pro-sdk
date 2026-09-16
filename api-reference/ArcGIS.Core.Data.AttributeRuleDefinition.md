# AttributeRuleDefinition

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of an attribute rule.  See <xref href="ArcGIS.Core.Data.TableDefinition.GetAttributeRules(ArcGIS.Core.Data.AttributeRuleType)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class AttributeRuleDefinition : CoreObjectsBase, IDisposable
```


## Members

### GetAttributeRuleType()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the attribute rule type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributeRuleType GetAttributeRuleType()
```
### GetDescription()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the attribute rule description.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetDescription()
```
### GetErrorMessage()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the error message that will be returned if the rule is violated.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetErrorMessage()
```
### GetErrorNumber()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the error number that will be returned if the rule is violated.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetErrorNumber()
```
### GetEvaluationOrder()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the order in which the rule is run.<br>
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetEvaluationOrder()
```
### GetExcludeFromClientEvaluation()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets if the rule is to be excluded from client evaluation - that is the rule will NOT be evaluated by the application or client
locally before applying the edits to the workspace. Instead the rule will only be evaluated once edits are applied.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetExcludeFromClientEvaluation()
```
### GetFieldName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the name of the field to which this rule will be applied.  An empty string is returned if no field is specified.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetFieldName()
```
### GetIsBatch()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets if the rule evaluation will be run in batch mode.</p>


```csharp
public bool GetIsBatch()
```
### GetIsEnabled()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets if the rule is enabled.</p>


```csharp
public bool GetIsEnabled()
```
### GetIsFieldEditable()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets if the field that the rule applies to is editable.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetIsFieldEditable()
```
### GetMinimumArcadeVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the minimum Arcade version required for the expression in this rule.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetMinimumArcadeVersion()
```
### GetName()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the attribute rule name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName()
```
### GetScriptExpression()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the Arcade expression that defines the rule.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetScriptExpression()
```
### GetSeverity()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the severity of the error if the rule is violated.  This is applicable to validation rule types only.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetSeverity()
```
### GetSubtype()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the subtype to which this rule will be applied, if the dataset has subtypes. /&gt;.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Subtype GetSubtype()
```
### GetTags()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the set of tags for the rule.  Mutliple tags are returned as a semicolon delimited string.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetTags()
```
### GetTriggeringEvents()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleDefinition.yml" sourcestartlinenumber="1">Gets the editing events that will trigger the attribute rule to take effect. This parameter is valid for calculation and constraint rule types only.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public AttributeRuleTriggers GetTriggeringEvents()
```


