# QueryBuilderControl

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.Controls.html">Controls</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">The QueryBuilderControl is a configurable control that provides
a UI for building a query expression against a layer or table.</p>


## Object Signature

```csharp
public class QueryBuilderControl : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild, IComponentConnector
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Bind a QueryBuilderControlProperties instance to the QueryBuilderControl to
provide the desired configuration. A mapMember (layer or table) must be set. An optional Expression can also be set.
Developers can use a callback with the ExpressionChanged event to receive expression changed notifications. The ValidateExpression method
is also available to validate the current query expression.</p>
<pre><code sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="6">        &lt;p&gt;&lt;/p&gt;&lt;p&gt;&lt;/p&gt;&lt;img src=&quot;images/ArcGIS.Desktop.Mapping/QueryBuilderControl.png&quot; alt=&quot;Query Builder Control&quot; /&gt;&lt;img src=&quot;images/ArcGIS.Desktop.Mapping/QueryBuilderControl_Query.png&quot; alt=&quot;Query Builder Control with Query&quot; /&gt;
</code></pre>


## Members

### QueryBuilderControl()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Default constructor. This will be called via the parent control or window on
which the QueryBuilderControl is hosted.</p>


```csharp
public QueryBuilderControl()
```
### ClearExpression()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Clear the current expression in the QueryBuilderControl.</p>


```csharp
public void ClearExpression()
```
### ConfigureControl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Gets and sets the QueryBuilderControlProperties to be used to configure the
QueryBuilderControl.</p>


```csharp
public QueryBuilderControlProperties ConfigureControl { get; set; }
```
### ConfigureControlProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">DependencyProperty to which a QueryBuilderControlProperties used to
configure the QueryBuilderControl can be bound.</p>


```csharp
public static readonly DependencyProperty ConfigureControlProperty
```
### Expression

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Gets the current query Expression.</p>


```csharp
public string Expression { get; }
```
### ExpressionChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">The ExpressionChanged event is raised when the query expression is changed in the
control UI.</p>


```csharp
public event ExpressionChangedEventHandler ExpressionChanged
```
### ExpressionProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Read-only dependency property for the query expression.</p>


```csharp
public static readonly DependencyProperty ExpressionProperty
```
### InitializeComponent()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">InitializeComponent</p>


```csharp
public void InitializeComponent()
```
### IsEditing

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Gets whether editing is currently occuring.</p>


```csharp
public bool IsEditing { get; }
```
### IsEditingProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Read-only dependency property for the query IsEditing flag. Determine whether the QueryBuilderControl is currently editing a clause.</p>


```csharp
public static readonly DependencyProperty IsEditingProperty
```
### IsValid

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Gets whether the current Expression is valid.</p>


```csharp
public bool IsValid { get; }
```
### IsValidProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Read-only dependency property for the IsValid property. Determine whether the current Expression is valid.</p>


```csharp
public static readonly DependencyProperty IsValidProperty
```
### Message

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Gets the current validation Message.</p>


```csharp
public string Message { get; }
```
### MessageProperty

- Kind: field

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Read-only dependency property for the query validation Message.</p>


```csharp
public static readonly DependencyProperty MessageProperty
```
### OnExpressionChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">This raises our 'public' event. Users can hook up delegates or use the Expression
property.</p>


```csharp
protected virtual void OnExpressionChanged()
```
### ValidateExpressionAsync(bool)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Mapping.Controls.QueryBuilderControl.yml" sourcestartlinenumber="1">Validate the current expression in the QueryBuilderControl.  Set the <code class="paramref">verifySyntaxOnly</code> to true to
verify SQL syntax only.  Use false to validate the expression for syntax and determine whether any rows will be returned.</p>


```csharp
public Task<bool> ValidateExpressionAsync(bool verifySyntaxOnly)
```


