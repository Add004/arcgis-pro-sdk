# Rule

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Rule.yml" sourcestartlinenumber="1">Represents a rule in the utility network.  These define how features can be associated with each other through connectivity, containment, and attachment.</p>


## Object Signature

```csharp
public sealed class Rule
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Rule.yml" sourcestartlinenumber="1">Rule objects are obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetRules" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Rule.yml" sourcestartlinenumber="1">Gets a numeric ID that can be used to identify a rule</p>


```csharp
public int ID { get; }
```
### RuleElements

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Rule.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.RuleElement" data-throw-if-not-resolved="false"></xref> objects that make up this rule.  These elements describe the features that participate in the rule.</p>


```csharp
public IReadOnlyList<RuleElement> RuleElements { get; }
```
### Type

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Rule.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.UtilityNetwork.RuleType" data-throw-if-not-resolved="false"></xref> for this rule.</p>


```csharp
public RuleType Type { get; }
```


