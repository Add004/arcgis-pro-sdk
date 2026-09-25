# ElementEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.html">Layouts</a>.<a class="xref" href="ArcGIS.Desktop.Layouts.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Layouts.dll

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEventArgs.yml" sourcestartlinenumber="1">Provides data for the <xref href="ArcGIS.Desktop.Layouts.Events.ElementEvent?text=ElementEvent" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public class ElementEventArgs : EventArgs
```


## Members

### ElementEventArgs()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEventArgs.yml" sourcestartlinenumber="1">Default constructor</p>


```csharp
protected ElementEventArgs()
```
### Container

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEventArgs.yml" sourcestartlinenumber="1">Gets the element container.</p>


```csharp
public IElementContainer Container { get; }
```
### Elements

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEventArgs.yml" sourcestartlinenumber="1">Gets the list of elements that have been updated.</p>


```csharp
public IElement[] Elements { get; }
```
### Hint

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Layouts.Events.ElementEventArgs.yml" sourcestartlinenumber="1">Gets the event hint.</p>


```csharp
public ElementEventHint Hint { get; }
```


