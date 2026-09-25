# ArcadeScriptEngine

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Arcade.html">Arcade</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeScriptEngine.yml" sourcestartlinenumber="1">Use the ArcadeScriptEngine to create an <xref href="ArcGIS.Core.Arcade.ArcadeEvaluator" data-throw-if-not-resolved="false"></xref> to
execute an Arcade script.</p>


## Object Signature

```csharp
public sealed class ArcadeScriptEngine : IArcadeScriptEngine
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeScriptEngine.yml" sourcestartlinenumber="1">The current arcade version in use by the engine as well as the
minimum required version for a given expression + profile can also be
determined.<br>
Consult <a href="https://developers.arcgis.com/arcade/"></a> for the
complete Arcade reference</p>


## Members

### CreateEvaluator(CIMExpressionInfo, ArcadeProfile)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeScriptEngine.yml" sourcestartlinenumber="1">Creates an instance of an Arcade script evaluator.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public ArcadeEvaluator CreateEvaluator(CIMExpressionInfo expressionInfo, ArcadeProfile profile)
```
### GetRequiredVersion(CIMExpressionInfo, ArcadeProfile)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeScriptEngine.yml" sourcestartlinenumber="1">Gets the minimum required version of Arcade needed for the given expression.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetRequiredVersion(CIMExpressionInfo expressionInfo, ArcadeProfile profile)
```
### GetVersion()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeScriptEngine.yml" sourcestartlinenumber="1">Gets the current version of Arcade in use by this engine.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetVersion()
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Arcade.ArcadeScriptEngine.yml" sourcestartlinenumber="1">Gets the singleton ArcadeScriptEngine instance.</p>


```csharp
public static IArcadeScriptEngine Instance { get; }
```


