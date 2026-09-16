# ProvenanceBehavior

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.ProvenanceBehavior.yml" sourcestartlinenumber="1">Controls query behavior with respect to the Provenance Entity Type.</p>


## Object Signature

```csharp
public enum ProvenanceBehavior
```


## Members

### Exclude

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.ProvenanceBehavior.yml" sourcestartlinenumber="1">Query behaves as if there were no Provenance records in the graph, nor Provenance Entity Type defined in the data model.</p>


```csharp
Exclude = 0
```
### Include

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.ProvenanceBehavior.yml" sourcestartlinenumber="1">Query can reference the Provenance Entity Type. The result set may return provenance records.</p>


```csharp
Include = 1
```


