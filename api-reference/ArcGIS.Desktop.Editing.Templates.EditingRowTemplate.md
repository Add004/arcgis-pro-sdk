# EditingRowTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingRowTemplate.yml" sourcestartlinenumber="1">Defines how a new row is created for a particular <xref href="ArcGIS.Desktop.Mapping.MapMember?text=MapMember" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class EditingRowTemplate : EditingTemplate
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingRowTemplate.yml" sourcestartlinenumber="1">This implementation of <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate" data-throw-if-not-resolved="false"></xref> defines the attributes necessary to create a row within a single MapMember.</p>


## Members

### Inspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingRowTemplate.yml" sourcestartlinenumber="1">Gets the Inspector that contains the Attributes associated with this EditingTemplate.</p>


```csharp
public override Inspector Inspector { get; }
```
### PassesDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingRowTemplate.yml" sourcestartlinenumber="1">Gets whether this EditingTemplate's Attributes pass the MapMember's DefinitionQuery.</p>


```csharp
public override bool PassesDefinitionQuery { get; }
```


