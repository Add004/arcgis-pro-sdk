# ArcGISPortalManager

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Manages the collection of portals currently defined for Pro. Portals can be added to and
removed from the ArcGISPortalManager. The list of portals is shown on the Portals backstage
tab.</p>


## Object Signature

```csharp
public class ArcGISPortalManager
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">ArcGISPortalManager is a singleton. It is accessed via its <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager.Current" data-throw-if-not-resolved="false"></xref> property.<br>
Out of the box you will always have a portal entry defined for arcgis.com (ArcGIS Online). This
portal entry cannot be deleted.</p>


## Members

### AddPortal(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Add the specified portal represented by the provided portal Uri to the
list of portals. This will result in the <xref href="ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEvent" data-throw-if-not-resolved="false"></xref>
being published.
This method should be called from within a QueuedTask or System.Threading.Task unless
the caller is within <xref href="ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.OnApplicationInitializing(System.ComponentModel.CancelEventArgs)" data-throw-if-not-resolved="false"></xref>
in which case the main thread should be used.<br></p>


```csharp
public ArcGISPortal AddPortal(Uri portalUri)
```
### Current

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Gets the singleton ArcGISPortalManager instance</p>


```csharp
public static ArcGISPortalManager Current { get; }
```
### EditPortal(ArcGISPortal, Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Change the Uri of the existing portal to be the new Portal Uri.
This method should be called from within a QueuedTask or System.Threading.Task unless
the caller is within <xref href="ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.OnApplicationInitializing(System.ComponentModel.CancelEventArgs)" data-throw-if-not-resolved="false"></xref>
in which case the main thread should be used.<br></p>


```csharp
public ArcGISPortal EditPortal(ArcGISPortal existingPortalObj, Uri newPortalUri)
```
### GetActivePortal()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Get the currently active portal. This is the portal that has been set as the Active Portal
either via the API or on the &quot;Portals&quot; backstage tab.</p>


```csharp
public ArcGISPortal GetActivePortal()
```
### GetPortal(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Get the Portal from the list of portals based on the provided portalURI</p>


```csharp
public ArcGISPortal GetPortal(Uri portalUri)
```
### GetPortals()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Get the enumeration of portals. This list correlates with the list of portals
on the &quot;Portals&quot; tab on the Pro backstage.</p>


```csharp
public IEnumerable<ArcGISPortal> GetPortals()
```
### RemovePortal(Uri)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Remove the portal represented by the provided portal Uri from the list
of portals. This will result in the <xref href="ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEvent" data-throw-if-not-resolved="false"></xref>
being published.</p>


```csharp
public bool RemovePortal(Uri portalUri)
```
### SetActivePortal(ArcGISPortal)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.ArcGISPortalManager.yml" sourcestartlinenumber="1">Sets the currently active portal. This will result in the <xref href="ArcGIS.Desktop.Core.Events.ActivePortalChangedEvent" data-throw-if-not-resolved="false"></xref>
being published.
This method should be called from within a QueuedTask or System.Threading.Task unless
the caller is within <xref href="ArcGIS.Desktop.Framework.Contracts.ConfigurationManager.OnApplicationInitializing(System.ComponentModel.CancelEventArgs)" data-throw-if-not-resolved="false"></xref>
in which case the main thread should be used.<br></p>


```csharp
public bool SetActivePortal(ArcGISPortal portalObj)
```


