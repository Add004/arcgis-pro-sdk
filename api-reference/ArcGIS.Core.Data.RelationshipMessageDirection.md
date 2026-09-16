# RelationshipMessageDirection

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RelationshipMessageDirection.yml" sourcestartlinenumber="1">The message notification direction when origin and destination objects are changed.</p>


## Object Signature

```csharp
public enum RelationshipMessageDirection
```


## Members

### Backward

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipMessageDirection.yml" sourcestartlinenumber="1">Message notifications are sent to related origin objects when the destination object is changed.</p>


```csharp
Backward = 3
```
### Both

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipMessageDirection.yml" sourcestartlinenumber="1">Message notifications are sent both in the forward and backward direction when an object is changed.</p>


```csharp
Both = 4
```
### Forward

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipMessageDirection.yml" sourcestartlinenumber="1">Message notifications are sent to related destination objects when the origin object is changed.</p>


```csharp
Forward = 2
```
### None

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipMessageDirection.yml" sourcestartlinenumber="1">No message notifications are sent.</p>


```csharp
None = 1
```


