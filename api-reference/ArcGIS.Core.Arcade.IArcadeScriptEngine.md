# IArcadeScriptEngine

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Arcade.html">Arcade</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Arcade.IArcadeScriptEngine.yml" sourcestartlinenumber="1">This interface allows you to create an <xref href="ArcGIS.Core.Arcade.ArcadeEvaluator" data-throw-if-not-resolved="false"></xref>
for interactive execution of an arcade script.</p>


## Object Signature

```csharp
public interface IArcadeScriptEngine
```


## Members

### CreateEvaluator(CIMExpressionInfo, ArcadeProfile)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.IArcadeScriptEngine.yml" sourcestartlinenumber="1">Creates an instance of an Arcade script evaluator.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
ArcadeEvaluator CreateEvaluator(CIMExpressionInfo expressionInfo, ArcadeProfile profile)
```
### GetRequiredVersion(CIMExpressionInfo, ArcadeProfile)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.IArcadeScriptEngine.yml" sourcestartlinenumber="1">Gets the minimum required version of Arcade needed for the given expression.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
string GetRequiredVersion(CIMExpressionInfo expressionInfo, ArcadeProfile profile)
```
### GetVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.IArcadeScriptEngine.yml" sourcestartlinenumber="1">Gets the current version of Arcade in use by this engine.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
string GetVersion()
```


