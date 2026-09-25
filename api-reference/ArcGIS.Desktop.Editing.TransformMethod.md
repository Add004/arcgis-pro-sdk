# TransformMethod

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformMethod.yml" sourcestartlinenumber="1">A base class used to represent a transformation method.
For use with <xref href="ArcGIS.Desktop.Editing.EditOperation.Transform(ArcGIS.Desktop.Mapping.Layer%2cArcGIS.Desktop.Editing.TransformMethod)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.EditOperation.Transform(ArcGIS.Desktop.Mapping.SelectionSet%2cArcGIS.Desktop.Editing.TransformMethod)" data-throw-if-not-resolved="false"></xref>.
Possible transformation methods include <xref href="ArcGIS.Desktop.Editing.TransformByLinkLayer" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Desktop.Editing.TransformByLinkLines" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public abstract class TransformMethod
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformMethod.yml" sourcestartlinenumber="1">Do not attempt to create a custom class inheriting from this type.</p>


## Members

### TransformMethod()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformMethod.yml" sourcestartlinenumber="1">Constructs a new <xref href="ArcGIS.Desktop.Editing.TransformMethod" data-throw-if-not-resolved="false"></xref> object.</p>


```csharp
public TransformMethod()
```
### TransformType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.TransformMethod.yml" sourcestartlinenumber="1">Gets or sets the type of transformation to perform.</p>


```csharp
public TransformMethodType TransformType { get; set; }
```


