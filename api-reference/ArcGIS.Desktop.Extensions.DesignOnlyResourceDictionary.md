# DesignOnlyResourceDictionary

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Extensions.html">Extensions</a>
- Assembly: ArcGIS.Desktop.Extensions.dll

<p sourcefile="api/ArcGIS.Desktop.Extensions.DesignOnlyResourceDictionary.yml" sourcestartlinenumber="1">The design only resource dictionary is a specialized resource dictionary
that references content only in design mode.</p>


## Object Signature

```csharp
public class DesignOnlyResourceDictionary : ResourceDictionary, IDictionary, ICollection, IEnumerable, ISupportInitialize, IUriContext, INameScope
```


## Members

### DesignOnlyResourceDictionary()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Extensions.DesignOnlyResourceDictionary.yml" sourcestartlinenumber="1">The design only resource dictionary is a specialized resource dictionary
that references content only in design mode.</p>


```csharp
public DesignOnlyResourceDictionary()
```
### Source

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Extensions.DesignOnlyResourceDictionary.yml" sourcestartlinenumber="1">This dictionary only sets the URI when the VS XAML designer is active.
During runtime the resource dictionary is empty.
Here is an example of a URI:
Source=&quot;pack://application:,,,/ArcGIS.Desktop.Framework;component\Themes\Default.xaml&quot;
Consequently this property returns source (URI) only in design mode
and hence resolves the designer's requirements for resources
During runtime WPF gets the resource from Pro's framework, hence the
resource is set the properly theme.</p>


```csharp
public Uri Source { get; set; }
```


