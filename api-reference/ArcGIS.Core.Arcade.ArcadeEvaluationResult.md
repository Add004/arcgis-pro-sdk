# ArcadeEvaluationResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Arcade.html">Arcade</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluationResult.yml" sourcestartlinenumber="1">Represents the result of an Arcade evaluation.</p>


## Object Signature

```csharp
public sealed class ArcadeEvaluationResult : CoreObjectsBase, IDisposable
```


## Members

### CastTo(ExpressionReturnType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluationResult.yml" sourcestartlinenumber="1">Convert the result of the expression to the given type.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object CastTo(ExpressionReturnType returnType)
```
### GetResult()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluationResult.yml" sourcestartlinenumber="1">Gets the result of the expression.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetResult()
```
### IsEqual(ArcadeEvaluationResult)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeEvaluationResult.yml" sourcestartlinenumber="1">Checks to see if two evaluation results are equal. This is a value comparison.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool IsEqual(ArcadeEvaluationResult evaluationResult)
```


