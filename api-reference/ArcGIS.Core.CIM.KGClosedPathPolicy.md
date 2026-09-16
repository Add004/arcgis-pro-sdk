# KGClosedPathPolicy

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.KGClosedPathPolicy.yml" sourcestartlinenumber="1">The closed path policy, i.e whether we allow, forbid, or require that result paths are closed.</p>
<p sourcefile="api/ArcGIS.Core.CIM.KGClosedPathPolicy.yml" sourcestartlinenumber="3">A path is closed when the start and end vertices of the path are the same.</p>


## Object Signature

```csharp
public enum KGClosedPathPolicy
```


## Members

### Allow

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGClosedPathPolicy.yml" sourcestartlinenumber="1">Allow closed paths.</p>


```csharp
Allow = 1
```
### Forbid

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGClosedPathPolicy.yml" sourcestartlinenumber="1">Forbid closed paths.</p>


```csharp
Forbid = 0
```
### Require

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGClosedPathPolicy.yml" sourcestartlinenumber="1">Require that all paths are closed.</p>


```csharp
Require = 2
```


