# SelectionCombinationMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionCombinationMethod.yml" sourcestartlinenumber="1">Define combination methods for selection operations. They determine how
the selection performed will combine with an existing selection.</p>


## Object Signature

```csharp
public enum SelectionCombinationMethod
```


## Members

### Add

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionCombinationMethod.yml" sourcestartlinenumber="1">Adds to the current selection.</p>


```csharp
Add = 1
```
### And

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionCombinationMethod.yml" sourcestartlinenumber="1">Selects from the current selection.</p>


```csharp
And = 3
```
### New

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionCombinationMethod.yml" sourcestartlinenumber="1">Creates a new selection.</p>


```csharp
New = 0
```
### Subtract

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionCombinationMethod.yml" sourcestartlinenumber="1">Subtracts from the current selection.</p>


```csharp
Subtract = 2
```
### XOR

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.SelectionCombinationMethod.yml" sourcestartlinenumber="1">Performs an 'exclusive or' with the current selection.</p>


```csharp
XOR = 4
```


