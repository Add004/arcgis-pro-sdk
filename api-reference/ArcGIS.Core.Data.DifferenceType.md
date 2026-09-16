# DifferenceType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DifferenceType.yml" sourcestartlinenumber="1">Specifies the type of difference in the row found between the source time and the difference time.</p>


## Object Signature

```csharp
public enum DifferenceType
```


## Members

### DeleteNoChange

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DifferenceType.yml" sourcestartlinenumber="1">Row has been deleted in the source and not changed in the difference.</p>


```csharp
DeleteNoChange = 1
```
### DeleteUpdate

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DifferenceType.yml" sourcestartlinenumber="1">Row has been deleted in the source and updated in the difference.</p>


```csharp
DeleteUpdate = 5
```
### Insert

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DifferenceType.yml" sourcestartlinenumber="1">Row has been inserted in the source.</p>


```csharp
Insert = 0
```
### UpdateDelete

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DifferenceType.yml" sourcestartlinenumber="1">Row has been updated in the source and deleted in the difference.</p>


```csharp
UpdateDelete = 4
```
### UpdateNoChange

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DifferenceType.yml" sourcestartlinenumber="1">Row has been updated in the source and not changed in the difference.</p>


```csharp
UpdateNoChange = 2
```
### UpdateUpdate

- Kind: field

<p sourcefile="api/ArcGIS.Core.Data.DifferenceType.yml" sourcestartlinenumber="1">Row has been updated in both the source and difference.</p>


```csharp
UpdateUpdate = 3
```


