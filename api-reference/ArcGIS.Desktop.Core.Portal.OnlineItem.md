# OnlineItem

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.OnlineItem.yml" sourcestartlinenumber="1">Base class for portal entities</p>


## Object Signature

```csharp
public class OnlineItem : Item, IMetadata, ICloneable
```


## Members

### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.OnlineItem.yml" sourcestartlinenumber="1">Make a clone of the online item</p>


```csharp
public object Clone()
```
### Created

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.OnlineItem.yml" sourcestartlinenumber="1">Gets the date of creation or null if one was not specified on the original item</p>


```csharp
public DateTime Created { get; protected set; }
```
### Init(Dictionary&lt;string, string&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.OnlineItem.yml" sourcestartlinenumber="1">An online item must be initialized before use.</p>


```csharp
protected OnlineItem Init(Dictionary<string, string> onlineItemValues)
```
### PortalUri

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.OnlineItem.yml" sourcestartlinenumber="1">Gets the Uri of the associated portal</p>


```csharp
public Uri PortalUri { get; protected set; }
```


