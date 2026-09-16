# RelationshipSplitPolicy

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Specifies the split policy of the relationship class.</p>


## Object Signature

```csharp
public enum RelationshipSplitPolicy
```


## Members

### DeleteParts

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Delete the relationships and the part objects (with composite relationships).</p>


```csharp
DeleteParts = 6
```
### DeleteRelationship

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Delete the relationships.</p>


```csharp
DeleteRelationship = 5
```
### DuplicateRelatedObjects

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Duplicate the related objects in destination class.</p>


```csharp
DuplicateRelatedObjects = 7
```
### PreserveOnAll

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Preserve relationships on both resulting features (not valid with 1:1, 1:m).</p>


```csharp
PreserveOnAll = 4
```
### PreserveOnLargest

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Preserve relationships on the largest resulting feature.</p>


```csharp
PreserveOnLargest = 2
```
### PreserveOnSmallest

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Preserve relationships on the smallest resulting feature.</p>


```csharp
PreserveOnSmallest = 3
```
### UseDefault

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.RelationshipSplitPolicy.yml" sourcestartlinenumber="1">Use the default policy.</p>


```csharp
UseDefault = 1
```


