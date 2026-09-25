# ExecuteModeType

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.ExecuteModeType.yml" sourcestartlinenumber="1">An enumeration of possible execute mode types. Used in an <xref href="ArcGIS.Desktop.Editing.EditOperation" data-throw-if-not-resolved="false"></xref> to control the order of edit function execution.</p>


## Object Signature

```csharp
public enum ExecuteModeType
```


## Members

### Default

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.ExecuteModeType.yml" sourcestartlinenumber="1">Edits are grouped together and executed in the default manner regardless of the order they are defined on the <xref href="ArcGIS.Desktop.Editing.EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
Default = 0
```
### Sequential

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Editing.ExecuteModeType.yml" sourcestartlinenumber="1">Edits are executed in a sequential manner in the order they are defined on the <xref href="ArcGIS.Desktop.Editing.EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
Sequential = 1
```


