# TerminalConfiguration

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Represents a configuration of <xref href="ArcGIS.Core.Data.UtilityNetwork.Terminal" data-throw-if-not-resolved="false"></xref> objects that are assigned to zero or more AssetTypes.</p>


## Object Signature

```csharp
public sealed class TerminalConfiguration
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Terminal configurations can be obtained through two different methods:</p>
<ul><li><xref href="ArcGIS.Core.Data.UtilityNetwork.UtilityNetworkDefinition.GetTerminalConfigurations" data-throw-if-not-resolved="false"></xref></li><li><xref href="ArcGIS.Core.Data.UtilityNetwork.AssetType.GetTerminalConfiguration" data-throw-if-not-resolved="false"></xref></li></ul>


## Members

### DefaultConfigurationPath

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Gets the default <xref href="ArcGIS.Core.Data.UtilityNetwork.ConfigurationPath" data-throw-if-not-resolved="false"></xref> defined for this TerminalConfiguration.<br>
If this property returns <b>null</b>, that means configuration paths do not apply to this TerminalConfiguration.</p>


```csharp
public ConfigurationPath DefaultConfigurationPath { get; }
```
### Directionality

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Specifies the directionality setting of terminals on a device.</p>


```csharp
public Directionality Directionality { get; }
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Gets a numeric ID that can be used to identify the terminal configuration.</p>


```csharp
public int ID { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Gets a user-readable string that describes the terminal configuration</p>


```csharp
public string Name { get; }
```
### Terminals

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Gets a list of <xref href="ArcGIS.Core.Data.UtilityNetwork.Terminal" data-throw-if-not-resolved="false"></xref> objects that define this terminal configuration.</p>


```csharp
public IReadOnlyList<Terminal> Terminals { get; }
```
### ValidConfigurationPaths

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.yml" sourcestartlinenumber="1">Gets the valid configuration paths that constrain the flow paths between pairs of terminals.
If this TerminalConfiguration instance does not have <xref href="ArcGIS.Core.Data.UtilityNetwork.ConfigurationPath" data-throw-if-not-resolved="false"></xref>s defined,
an empty <xref href="System.Collections.Generic.IReadOnlyList%601" data-throw-if-not-resolved="false"></xref> is returned.</p>


```csharp
public IReadOnlyList<ConfigurationPath> ValidConfigurationPaths { get; }
```


