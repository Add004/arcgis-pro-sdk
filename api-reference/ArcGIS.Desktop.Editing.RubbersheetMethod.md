# RubbersheetMethod

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetMethod.yml" sourcestartlinenumber="1">A base class used to represent a rubbersheet method.
For use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Rubbersheet(ArcGIS.Desktop.Mapping.Layer%2cArcGIS.Desktop.Editing.RubbersheetMethod)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.EditOperation.Rubbersheet(ArcGIS.Desktop.Mapping.SelectionSet%2cArcGIS.Desktop.Editing.RubbersheetMethod)" data-throw-if-not-resolved="false"></xref>.
Possible transformation methods include <xref href="ArcGIS.Desktop.Editing.RubbersheetByLayers" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.RubbersheetByGeometries" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class RubbersheetMethod
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetMethod.yml" sourcestartlinenumber="1">Do not attempt to create a custom class inheriting from this type.</p>


## Members

### RubbersheetMethod()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetMethod.yml" sourcestartlinenumber="1">Constructs a new <xref href="ArcGIS.Desktop.Editing.RubbersheetMethod" data-throw-if-not-resolved="false"></xref> object.</p>


```csharp
public RubbersheetMethod()
```
### RubbersheetType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.RubbersheetMethod.yml" sourcestartlinenumber="1">Gets or sets the rubbersheet method to use.</p>


```csharp
public RubbersheetMethodType RubbersheetType { get; set; }
```


