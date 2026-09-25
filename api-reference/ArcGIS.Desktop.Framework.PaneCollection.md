# PaneCollection

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Framework.html">Framework</a>
- Assembly: ArcGIS.Desktop.Framework.dll

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Panes collection object.  This class contains
all active instances of panes as well as supplying the
mechanism for creating new instances of panes.</p>


## Object Signature

```csharp
public sealed class PaneCollection : IEnumerable
```


## Members

### ActivePane

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Gets the currently active Pane.</p>


```csharp
public Pane ActivePane { get; }
```
### CloseAllPanes()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Close all open panes.</p>


```csharp
public void CloseAllPanes()
```
### ClosePane(uint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Close the pane identified by the specified instance ID.</p>


```csharp
public void ClosePane(uint id)
```
### Count

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Gets the number of currently open panes.</p>


```csharp
public int Count { get; }
```
### Create(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Create a new instance of the pane identified by the specified DAML ID.</p>


```csharp
public Pane Create(string id)
```
### Create(string, params object[])

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Creates a new instance of the specified pane using the supplied arguments.</p>


```csharp
public Pane Create(string id, params object[] param)
```
### Find(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Returns an array of Panes matching the specified DAML identifier.</p>


```csharp
public List<Pane> Find(string damlID)
```
### FindPane(uint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Finds the pane identified by the specified instance identifier.</p>


```csharp
public Pane FindPane(uint instanceID)
```
### GetEnumerator()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Returns an enumerator that iterates through the collection.</p>


```csharp
public IEnumerator GetEnumerator()
```
### this[int]

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Gets the pane at the specified index.</p>


```csharp
public Pane this[int index] { get; }
```
### RemovePermanentPane(uint)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Framework.PaneCollection.yml" sourcestartlinenumber="1">Closes a singleton pane.</p>


```csharp
public void RemovePermanentPane(uint id)
```


