# ViewModelBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ViewModelBase.yml" sourcestartlinenumber="1">Base class for ViewModels. Implements INotifyPropertyChange.</p>


## Object Signature

```csharp
public abstract class ViewModelBase : PropertyChangedBase, INotifyPropertyChanged
```


## Members

### ViewModelBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ViewModelBase.yml" sourcestartlinenumber="1">Base class for ViewModels. Implements INotifyPropertyChange.</p>


```csharp
protected ViewModelBase()
```
### Model

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.ViewModelBase.yml" sourcestartlinenumber="1">Gets or sets the view-model's model object.</p>


```csharp
public object Model { get; set; }
```


