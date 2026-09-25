# RelayCommand

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">An implementation of ICommand.</p>


## Object Signature

```csharp
public class RelayCommand : PropertyChangedBase, INotifyPropertyChanged, ICommand
```

## Remarks

<p>
            RelayCommands are helpful in decoupling the user interface from the logic that needs to run when a button is clicked
            for example.
            </p>
        <p>
            The framework's RelayCommand implementation is special in that by default it will add the command to the application's 
            main message pump meaning its CanExecute function will automatically be called several times a second. If you do not
            need this behavior, set 
<pre><code class="lang-csharp">supportsOnUpdate</code></pre>
 to false in the appropriate constructor. If you do use this behavior,
            make sure you <xref href="ArcGIS.Desktop.Framework.RelayCommand.Disconnect" data-throw-if-not-resolved="false"></xref> the command from the pump when your dialog closes.
            
        <p>
            RelayCommands automatically disable whenever the primary worker thread is busy. To override this behavior set
<pre><code sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="16">        &lt;pre&gt;&lt;code class=&quot;lang-csharp&quot;&gt;disableWhenBusy&lt;/code&gt;&lt;/pre&gt;
</code></pre>
<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="17">to false in the appropriate constructor.
</p>
<p>
Note, RelayCommands in the message pump automatically disable once the application begins to shutdown.
</p>


## Members

### RelayCommand(Action, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Action execute, bool supportsOnUpdate = true)
```
### RelayCommand(Action, Func&lt;bool&gt;, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Action execute, Func<bool> canExecute, bool supportsOnUpdate = true, bool disableWhenBusy = true)
```
### RelayCommand(Action&lt;object&gt;, Func&lt;bool&gt;, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Action<object> execute, Func<bool> canExecute, bool supportsOnUpdate = true, bool disableWhenBusy = true)
```
### RelayCommand(Action&lt;object&gt;, Func&lt;object, bool&gt;, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Action<object> execute, Func<object, bool> canExecute, bool supportsOnUpdate = true, bool disableWhenBusy = true)
```
### RelayCommand(Func&lt;object, Task&gt;, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Func<object, Task> execute, bool supportsOnUpdate = true)
```
### RelayCommand(Func&lt;object, Task&gt;, Func&lt;bool&gt;, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Func<object, Task> execute, Func<bool> canExecute, bool supportsOnUpdate = true, bool disableWhenBusy = true)
```
### RelayCommand(Func&lt;object, Task&gt;, Func&lt;object, bool&gt;, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Func<object, Task> execute, Func<object, bool> canExecute, bool supportsOnUpdate = true, bool disableWhenBusy = true)
```
### RelayCommand(Func&lt;Task&gt;, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Func<Task> execute, bool supportsOnUpdate = true)
```
### RelayCommand(Func&lt;Task&gt;, Func&lt;bool&gt;, bool, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(Func<Task> execute, Func<bool> canExecute, bool supportsOnUpdate = true, bool disableWhenBusy = true)
```
### RelayCommand(object, MethodInfo, PropertyInfo, bool)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Instantiates a new RelayCommand instance.</p>


```csharp
public RelayCommand(object targetObject, MethodInfo execute, PropertyInfo canExecute, bool supportsOnUpdate = true)
```
### CanExecute(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Gets whether the command can be executed.</p>


```csharp
public virtual bool CanExecute(object parameter)
```
### CanExecuteChanged

- Kind: event

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Occurs when the CanExecute property changes.</p>


```csharp
public event EventHandler CanExecuteChanged
```
### Disconnect()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Removes the command from the the OnUpdate message queue.</p>


```csharp
public void Disconnect()
```
### Execute(object)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Executes the command.</p>


```csharp
public virtual void Execute(object parameter)
```
### RaiseCanExecuteChanged()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Raises the CanExecuteChanged event.</p>


```csharp
public void RaiseCanExecuteChanged()
```
### Reconnect()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.RelayCommand.yml" sourcestartlinenumber="1">Adds the command back to the the OnUpdate message queue.</p>


```csharp
public void Reconnect()
```


