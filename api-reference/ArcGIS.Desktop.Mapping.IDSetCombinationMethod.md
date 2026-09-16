# IDSetCombinationMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.KnowledgeGraph.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDSetCombinationMethod.yml" sourcestartlinenumber="1">Defines combination methods for setting Link Chart content operations. They determine how
the <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet" data-throw-if-not-resolved="false"></xref> specified will combine with an existing <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet" data-throw-if-not-resolved="false"></xref>.
See <xref href="ArcGIS.Desktop.Mapping.KnowledgeGraphMappingExtensions.SetLinkChartContent(ArcGIS.Desktop.Mapping.Map%2cArcGIS.Desktop.Mapping.KnowledgeGraphLayerIDSet%2cArcGIS.Desktop.Mapping.IDSetCombinationMethod)" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public enum IDSetCombinationMethod
```


## Members

### Add

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDSetCombinationMethod.yml" sourcestartlinenumber="1">Adds to the current ID set.</p>


```csharp
Add = 1
```
### New

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDSetCombinationMethod.yml" sourcestartlinenumber="1">Creates a new ID set.</p>


```csharp
New = 0
```
### Subtract

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.IDSetCombinationMethod.yml" sourcestartlinenumber="1">Subtracts from the current ID set.</p>


```csharp
Subtract = 2
```


