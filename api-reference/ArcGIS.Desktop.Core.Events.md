# ArcGIS.Desktop.Core.Events

- Type: namespace
- Assembly: ArcGIS.Desktop.Core.dll




## Members

### ActivePaneInitializedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePaneInitializedEvent.yml" sourcestartlinenumber="1">Occurs when a the active pane is fully initialized</p>


### ActivePaneInitializedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePaneInitializedEventArgs.yml" sourcestartlinenumber="1">Represents the state of the active pane, indicating it is fully initialized</p>


### ActivePortalChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePortalChangedEvent.yml" sourcestartlinenumber="1">Occurs when the active portal is changed on the <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager" data-throw-if-not-resolved="false"></xref></p>


### ActivePortalChangedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ActivePortalChangedEventArgs.yml" sourcestartlinenumber="1">Data for the <xref href="ArcGIS.Desktop.Core.Events.ActivePortalChangedEvent" data-throw-if-not-resolved="false"></xref></p>


### ArcGISPortalAddedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEvent.yml" sourcestartlinenumber="1">Occurs when the a portal is added to the <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager" data-throw-if-not-resolved="false"></xref></p>


### ArcGISPortalAddedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEventArgs.yml" sourcestartlinenumber="1">Data for the <xref href="ArcGIS.Desktop.Core.Events.ArcGISPortalAddedEvent" data-throw-if-not-resolved="false"></xref></p>


### ArcGISPortalRemovedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEvent.yml" sourcestartlinenumber="1">Occurs when a portal is removed from the <xref href="ArcGIS.Desktop.Core.ArcGISPortalManager" data-throw-if-not-resolved="false"></xref></p>


### ArcGISPortalRemovedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEventArgs.yml" sourcestartlinenumber="1">Data for the <xref href="ArcGIS.Desktop.Core.Events.ArcGISPortalRemovedEvent" data-throw-if-not-resolved="false"></xref></p>


### BrowseLocationsClearedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.BrowseLocationsClearedEvent.yml" sourcestartlinenumber="1">Occurs when a user clears the browser locations in the options dialog.</p>


### FavoritesChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.FavoritesChangedEvent.yml" sourcestartlinenumber="1">Provides information when the favorites collection is changed.</p>


### GPExecuteToolEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEvent.yml" sourcestartlinenumber="1">Occurs when a Geoprocessing Tool is executed</p>


### GPExecuteToolEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.GPExecuteToolEventArgs.yml" sourcestartlinenumber="1">Event argument for the <xref href="ArcGIS.Desktop.Core.Events.GPExecuteToolEvent" data-throw-if-not-resolved="false"></xref></p>


### PortalSignOnChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent.yml" sourcestartlinenumber="1">Occurs when the sign on state of a portal changes.</p>


### PortalSignOnChangedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.PortalSignOnChangedEventArgs.yml" sourcestartlinenumber="1">Data for the  <xref href="ArcGIS.Desktop.Core.Events.PortalSignOnChangedEvent" data-throw-if-not-resolved="false"></xref></p>


### ProProjectEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectEventArgs.yml" sourcestartlinenumber="1">Event arguments</p>


### ProProjectSavingEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingEvent.yml" sourcestartlinenumber="1">Occurs when a project has been saved</p>


### ProProjectSavingStripCredentialsEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectSavingStripCredentialsEvent.yml" sourcestartlinenumber="1">Occurs when a project has been saved with strip credentials attribute set to true
This event gives the opportunity to strip credentials from anything that the subscriber
may be persisting in the project. It's important to note that the projectID that is passed
is not the projectID of the currently open project. It is the projectID of the project that
is being opened in the background specifically for the purpose of stripping credentials.</p>


### ProProjectStripCredentialsEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProProjectStripCredentialsEventArgs.yml" sourcestartlinenumber="1">Event arguments</p>


### ProjectCloseCanceledEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectCloseCanceledEvent.yml" sourcestartlinenumber="1">Occurs when the closing of a project in canceled</p>


### ProjectClosedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosedEvent.yml" sourcestartlinenumber="1">Occurs when a project has closed</p>


### ProjectClosingEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEvent.yml" sourcestartlinenumber="1">Occurs when a project is in the process of closing</p>


### ProjectClosingEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectClosingEventArgs.yml" sourcestartlinenumber="1">Represents the project on which the ProjectClosingEvent is operating</p>


### ProjectEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectEventArgs.yml" sourcestartlinenumber="1">Represents the project on which an event operates, and an enumeration indicating how the
project was opened and created, if appropriate</p>


### ProjectHomeFolderChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEvent.yml" sourcestartlinenumber="1">Occurs when the home folder of the current project is changed after initialization. This event's subscribers will always be called on a worker thread.</p>


### ProjectHomeFolderChangedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectHomeFolderChangedEventArgs.yml" sourcestartlinenumber="1">Represents old and new values of the current project's home folder.</p>


### ProjectItemRemovingEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemRemovingEvent.yml" sourcestartlinenumber="1">Occurs before a project item is removed. It provides the opportunity to cancel.</p>


### ProjectItemRemovingEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemRemovingEventArgs.yml" sourcestartlinenumber="1">Provides the data for the <xref href="ArcGIS.Desktop.Core.Events.ProjectItemRemovingEvent?text=ProjectItemRemovingEvent" data-throw-if-not-resolved="false"></xref>.</p>


### ProjectItemsChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEvent.yml" sourcestartlinenumber="1">Occurs when a project item is added or removed</p>


### ProjectItemsChangedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectItemsChangedEventArgs.yml" sourcestartlinenumber="1">Represents the project on which the ProjectItemsChangedEvent is operating</p>


### ProjectOpenMode

- Kind: enum

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectOpenMode.yml" sourcestartlinenumber="1">Specifies how the project was opened and created, as appropriate</p>


### ProjectOpenedAsyncEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectOpenedAsyncEvent.yml" sourcestartlinenumber="1">Occurs when a project has been opened</p>


### ProjectOpenedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectOpenedEvent.yml" sourcestartlinenumber="1">Occurs when a project has been opened</p>


### ProjectSavedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectSavedEvent.yml" sourcestartlinenumber="1">Occurs when a project has been saved</p>


### ProjectSavingEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectSavingEvent.yml" sourcestartlinenumber="1">Occurs when a project in the process of being saved</p>


### ProjectUnitFormatsChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEvent.yml" sourcestartlinenumber="1">Event raised when any of the project unit formats are changed, new ones added
or existing ones removed. Unit format changes are per-project</p>


### ProjectUnitFormatsChangedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectUnitFormatsChangedEventArgs.yml" sourcestartlinenumber="1">Event argument for the project units changed event.</p>


### ProjectWindowSelectedItemsChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent.yml" sourcestartlinenumber="1">Occurs when the selection changes in either the Project dockpane (&quot;Catalog pane&quot;) or any
Project pane instance (&quot;Catalog view&quot;).</p>


### ProjectWindowSelectedItemsChangedEventArgs

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEventArgs.yml" sourcestartlinenumber="1">Event argument for the <xref href="ArcGIS.Desktop.Core.Events.ProjectWindowSelectedItemsChangedEvent" data-throw-if-not-resolved="false"></xref></p>


### SystemFavoritesChangedEvent

- Kind: class

<p sourcefile="api/ArcGIS.Desktop.Core.Events.SystemFavoritesChangedEvent.yml" sourcestartlinenumber="1">Provides information when the system favorites collection is changed.</p>




