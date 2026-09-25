# BuilderMethod

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Templates.html">Templates</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Defines a <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Builder?text=Builder" data-throw-if-not-resolved="false"></xref> that is
used in conjunction with an <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate.Part.Template?text=EditingRowTemplate" data-throw-if-not-resolved="false"></xref> to
automatically construct a feature when using an <xref href="ArcGIS.Desktop.Editing.Templates.EditingGroupTemplate?text=EditingGroupTemplate" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public abstract class BuilderMethod
```


## Members

### BuilderMethod(string, ImageSource, IEnumerable&lt;AttributeDef&gt;)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Constructs a BuilderMethod.</p>


```csharp
protected BuilderMethod(string name, ImageSource image, IEnumerable<AttributeDef> options)
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Gets the unique DAML identifier for this BuilderMethod.</p>


```csharp
public string ID { get; }
```
### Image

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Gets the icon for this BuilderMethod.</p>


```csharp
public ImageSource Image { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Gets the name of this BuilderMethod.</p>


```csharp
public string Name { get; }
```
### Options

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Gets the collection of value parameter definitions for this BuilderMethod.</p>


```csharp
public IReadOnlyCollection<AttributeDef> Options { get; }
```
### Tooltip(Part)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Gets text that will be displayed over the display of this BuilderMethod in the TemplateProperties dialog box.</p>


```csharp
public virtual string Tooltip(EditingGroupTemplate.Part part)
```
### Transform(Geometry, IReadOnlyDictionary&lt;string, object&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Templates.BuilderMethod.yml" sourcestartlinenumber="1">Performs a geometric transformation on the input Geometry, producing the output geometry or geometries in a manner
that is defined by a BuilderMethod's parameter values.</p>


```csharp
public abstract IEnumerable<Geometry> Transform(Geometry geometry, IReadOnlyDictionary<string, object> values)
```


