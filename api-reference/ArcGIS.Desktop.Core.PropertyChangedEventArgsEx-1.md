# PropertyChangedEventArgsEx&lt;T&gt;

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.PropertyChangedEventArgsEx-1.yml" sourcestartlinenumber="1">Used as the argument parameter of the INotifyPropertyChanged.PropertyChanged event handler for some properties.</p>


## Object Signature

```csharp
public class PropertyChangedEventArgsEx<T> : PropertyChangedEventArgs
```


## Members

### PropertyChangedEventArgsEx(string, T, T)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.PropertyChangedEventArgsEx-1.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
public PropertyChangedEventArgsEx(string propertyName, T oldValue, T newValue)
```
### NewValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.PropertyChangedEventArgsEx-1.yml" sourcestartlinenumber="1">The new value of the property specified by PropertyName.</p>


```csharp
public T NewValue { get; }
```
### OldValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.PropertyChangedEventArgsEx-1.yml" sourcestartlinenumber="1">The previous value of the property specified by PropertyName.</p>


```csharp
public T OldValue { get; }
```


