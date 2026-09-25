# EditingGroupTemplate

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Defines a grouping of existing <xref href="ArcGIS.Desktop.Editing.Templates.EditingRowTemplate" data-throw-if-not-resolved="false"></xref>s that can be used to create multiple features together.</p>


## Object Signature

```csharp
public sealed class EditingGroupTemplate : EditingTemplate
```

## Remarks

<p>
    This implementation of <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate" data-throw-if-not-resolved="false"></xref> defines a grouping of one or more existing
    EditingRowTemplates, whose definable properties include the same properties as feature templates,
    together with properties that set the primary template and tool category, additional templates,
    and builders.  Each EditingRowTemplate is stored within a <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part?text=Part" data-throw-if-not-resolved="false"></xref>
    along with the corresponding <xref href="ArcGIS.Desktop.Editing.Templates.BuilderMethod?text=BuilderMethod" data-throw-if-not-resolved="false"></xref>.
    </p>
<p>
    You create features or temporary geometry with the primary template.
    The other templates in the group are assigned builders that autogenerate additional features based on
    the geometry of the feature or features you create in the map. For example, if you assign a water main
    template as the primary template, you create the water mains in the map, and other templates such as
    fittings, gate valves, and hydrants can be configured to autogenerate these features at locations based
    on the geometry of the water main.
    </p>
<p>
  <b>Note:</b> an EditingGroupTemplate cannot be added to another EditingGroupTemplate.</p>


## Members

### BasePart

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part" data-throw-if-not-resolved="false"></xref> that contains the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.BaseTemplate" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public EditingGroupTemplate.Part BasePart { get; }
```
### BaseTemplate

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Gets the primary template for this EditingGroupTemplate.</p>


```csharp
public EditingRowTemplate BaseTemplate { get; }
```
### Builders

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Gets an System.Collections.Generic.IEnumerable of the <xref href="ArcGIS.Desktop.Editing.Templates.BuilderMethod" data-throw-if-not-resolved="false"></xref>s that are registered in the applciation DAML.</p>


```csharp
public static IReadOnlyCollection<BuilderMethod> Builders { get; }
```
### Children

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Gets the collection of <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part" data-throw-if-not-resolved="false"></xref>s that make up this EditingGroupTemplate.</p>


```csharp
public ReadOnlyCollection<EditingGroupTemplate.Part> Children { get; }
```
### Inspector

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Editing.Attributes.Inspector?text=Inspector" data-throw-if-not-resolved="false"></xref>
of the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.BaseTemplate" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override Inspector Inspector { get; }
```
### Map

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Desktop.Mapping.Map?text=Map" data-throw-if-not-resolved="false"></xref> of the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.BaseTemplate" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override Map Map { get; }
```
### PassesDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.yml" sourcestartlinenumber="1">Gets whether the <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.BaseTemplate" data-throw-if-not-resolved="false"></xref> passes <xref href="ArcGIS.Desktop.Editing.Templates.EditingTemplate.PassesDefinitionQuery?text=its+DefinitionQuery" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public override bool PassesDefinitionQuery { get; }
```


