# ArcadeEvaluator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Arcade.html">Arcade</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluator.yml" sourcestartlinenumber="1">Represents an instance of an Arcade script engine.</p>


## Object Signature

```csharp
public sealed class ArcadeEvaluator : CoreObjectsBase, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluator.yml" sourcestartlinenumber="1">An evaluator is created by the <xref href="ArcGIS.Core.Arcade.ArcadeScriptEngine" data-throw-if-not-resolved="false"></xref>.
The supported <xref href="ArcGIS.Core.Arcade.ArcadeEvaluator.ProfileVariablesUsed" data-throw-if-not-resolved="false"></xref> are controlled by the
current <xref href="ArcGIS.Core.Arcade.ArcadeProfile" data-throw-if-not-resolved="false"></xref> used to create the evaluator.</p>


## Members

### Evaluate(IEnumerable&lt;KeyValuePair&lt;string, object&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluator.yml" sourcestartlinenumber="1">Evaluates the expression given the profile variable set.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ArcadeEvaluationResult Evaluate(IEnumerable<KeyValuePair<string, object>> profileVariables)
```
### GetFields(string, Table)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluator.yml" sourcestartlinenumber="1">Gets a list of fields that are required to use the arcade script.
This method must be called on the MCT. Use QueuedTask.Run.</p>
<ul><li>The explicit fields that are used in the arcade script e.g. $feature.fields1</li><li>The implicit fields that are needed when calling specific functions e.g. Geometry(), FeatureSetByAssociation()</li><li>The wildcard fields e.g. expects($feature, "*")</li></ul>


```csharp
public IReadOnlyCollection<string> GetFields(string profileVariable, Table table)
```
### Profile

- Kind: property

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluator.yml" sourcestartlinenumber="1">Gets the profile which the evaluator was set up with.</p>


```csharp
public ArcadeProfile Profile { get; }
```
### ProfileVariablesUsed

- Kind: property

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluator.yml" sourcestartlinenumber="1">Gets the list of profile variables that are being used
in the expression.</p>


```csharp
public IReadOnlyCollection<string> ProfileVariablesUsed { get; }
```


