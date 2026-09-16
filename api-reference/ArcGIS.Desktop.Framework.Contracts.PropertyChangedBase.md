# PropertyChangedBase

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>.<a class="xref" href="ArcGIS.Desktop.Framework.Contracts.html">Contracts</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">A base class that implements the infrastructure for property change notification and automatically performs UI thread marshalling.</p>


## Object Signature

```csharp
public abstract class PropertyChangedBase : INotifyPropertyChanged
```


## Members

### PropertyChangedBase()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">A base class that implements the infrastructure for property change notification and automatically performs UI thread marshalling.</p>


```csharp
protected PropertyChangedBase()
```
### NotifyPropertyChanged(PropertyChangedEventArgs)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">Raises the PropertyChanged event for the specified property.</p>


```csharp
protected virtual void NotifyPropertyChanged(PropertyChangedEventArgs args)
```
### NotifyPropertyChanged(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">Raises the PropertyChanged event for the specified property.</p>


```csharp
protected virtual void NotifyPropertyChanged(string name = "")
```
### NotifyPropertyChanged&lt;T&gt;(Expression&lt;Func&lt;T&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">Raises the PropertyChanged event for the specified property.</p>


```csharp
protected virtual void NotifyPropertyChanged<T>(Expression<Func<T>> property)
```
### PropertyChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">Occurs when a property value changes.</p>


```csharp
public event PropertyChangedEventHandler PropertyChanged
```
### SetProperty&lt;T&gt;(ref T, T, Expression&lt;Func&lt;T&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">Sets a property value and calls NotifyPropertyChanged when the new value differs from the current value.</p>


```csharp
protected bool SetProperty<T>(ref T backingField, T value, Expression<Func<T>> property)
```
### SetProperty&lt;T&gt;(ref T, T, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.Contracts.PropertyChangedBase.yml" sourcestartlinenumber="1">Sets a property value and calls NotifyPropertyChanged when the new value differs from the current value.</p>


```csharp
protected bool SetProperty<T>(ref T backingField, T value, string name = "")
```


