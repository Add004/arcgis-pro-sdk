# DefinitionQueryBuilderControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">The DefinitionQueryBuilderControl is a configurable control that provides
a UI for building definition queries against a layer or table.</p>


## Object Signature

```csharp
public class DefinitionQueryBuilderControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Bind a <xref href="ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControlProperties" data-throw-if-not-resolved="false"></xref>  instance to the DefinitionQueryBuilderControl to
provide the desired configuration. A mapMember (layer or table) must be set in the <xref href="ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControlProperties" data-throw-if-not-resolved="false"></xref>.</p>
<pre><code sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="4">        &lt;p&gt;&lt;/p&gt;
</code></pre>


## Members

### DefinitionQueryBuilderControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the DefinitionQueryBuilderControl is hosted.</p>


```csharp
public DefinitionQueryBuilderControl()
```
### ActiveDefinitionQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Gets the active definition query in the DefinitionQueryBuilderControl. Returns null if there is no active definition query.</p>


```csharp
public DefinitionQuery ActiveDefinitionQuery { get; }
```
### ConfigureControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Gets and sets the <xref href="ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControlProperties" data-throw-if-not-resolved="false"></xref>  to be used to configure the
DefinitionQueryBuilderControl.</p>


```csharp
public DefinitionQueryBuilderControlProperties ConfigureControl { get; set; }
```
### ConfigureControlProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">DependencyProperty to which a DefinitionQueryBuilderControlProperties used to
configure the DefinitionQueryBuilderControl can be bound.</p>


```csharp
public static readonly DependencyProperty ConfigureControlProperty
```
### DefinitionQueries

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Gets the list of definition queries in the DefinitionQueryBuilderControl.</p>


```csharp
public IReadOnlyList<DefinitionQuery> DefinitionQueries { get; }
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsModified

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Gets the IsModified property.</p>


```csharp
public bool IsModified { get; }
```
### IsModifiedProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Identifies the IsModified dependency property.</p>


```csharp
public static readonly DependencyProperty IsModifiedProperty
```
### RemoveAllDefinitionQueries()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.DefinitionQueryBuilderControl.yml" sourcestartlinenumber="1">Removes all definition queries in the DefinitionQueryBuilderControl.</p>


```csharp
public void RemoveAllDefinitionQueries()
```


