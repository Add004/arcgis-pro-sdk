# AttributeRuleType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleType.yml" sourcestartlinenumber="1">Specifies the type of attribute rule operation.</p>


## Object Signature

```csharp
public enum AttributeRuleType
```


## Members

### All

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleType.yml" sourcestartlinenumber="1">All rules types.  When used with <xref href="ArcGIS.Core.Data.AttributeRuleManager.Evaluate(ArcGIS.Core.Data.AttributeRuleEvaluationDescription)" data-throw-if-not-resolved="false"></xref> this means
Calculation and Validation types as Constraint rules cannot be evaluated.  When used with <xref href="ArcGIS.Core.Data.TableDefinition.GetAttributeRules(ArcGIS.Core.Data.AttributeRuleType)" data-throw-if-not-resolved="false"></xref> this means
Calcuation, Constraint and Validation rule types.</p>


```csharp
All = 3
```
### Calculation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleType.yml" sourcestartlinenumber="1">Calculation rule.</p>


```csharp
Calculation = 0
```
### Constraint

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleType.yml" sourcestartlinenumber="1">Constraint rule.</p>


```csharp
Constraint = 1
```
### Validation

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.AttributeRuleType.yml" sourcestartlinenumber="1">Validation rule.</p>


```csharp
Validation = 2
```


