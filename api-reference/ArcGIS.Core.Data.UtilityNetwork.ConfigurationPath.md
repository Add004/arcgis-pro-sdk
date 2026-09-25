# ConfigurationPath

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ConfigurationPath.yml" sourcestartlinenumber="1">The configuration path class details the set of flow paths between <xref href="ArcGIS.Core.Data.UtilityNetwork.Terminal" data-throw-if-not-resolved="false"></xref>s for a given device configuration.</p>


## Object Signature

```csharp
public sealed class ConfigurationPath
```


## Members

### Description

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ConfigurationPath.yml" sourcestartlinenumber="1">Gets the description of this ConfigurationPath instance.</p>


```csharp
public string Description { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ConfigurationPath.yml" sourcestartlinenumber="1">Gets the name of this ConfigurationPath instance.</p>


```csharp
public string Name { get; }
```
### TerminalPaths

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.ConfigurationPath.yml" sourcestartlinenumber="1">Gets all the flow paths between pairs of terminals defined for this ConfigurationPath instance.</p>


```csharp
public IReadOnlyList<TerminalPath> TerminalPaths { get; }
```


