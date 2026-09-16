# ArcGIS.Core.Data.LinearReferencing

- Type: namespace
- Assembly: ArcGIS.Core.dll




## Members

### AngleType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.AngleType.yml" sourcestartlinenumber="1">Specifies the locating angle type for a <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>.</p>


### EventInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventInfo.yml" sourcestartlinenumber="1">Represents information for an event table. Each row in the table references an event, and its location is expressed as measurements along a route feature.</p>


### EventTableConfiguration

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventTableConfiguration.yml" sourcestartlinenumber="1">Describes an event table to hold events' information as the results of <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo.LocateFeatures(ArcGIS.Core.Data.FeatureClass%2cSystem.Double%2cArcGIS.Core.Data.LinearReferencing.EventTableConfiguration)" data-throw-if-not-resolved="false"></xref>.</p>


### EventType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.EventType.yml" sourcestartlinenumber="1">Specifies the type of Event. An Event is a feature that occurs along a route feature. Anything
that occurs on or describes a route feature can be an event. Examples might include pavement quality,
accident sites, and speed limits in the transportation field.</p>


### LineEventInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventInfo.yml" sourcestartlinenumber="1">Represents information for an event table with line events. Each row in the table references an event, and its location is expressed as
measurements along a route feature.</p>


### LineEventSourceOptions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventSourceOptions.yml" sourcestartlinenumber="1">Represents a configuration to create a dynamic feature class (<xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>) originating from line events using the dynamic
segmentation process.</p>


### LineEventTableConfiguration

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LineEventTableConfiguration.yml" sourcestartlinenumber="1">Describes a line event table to hold events' information as the results of <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo.LocateFeatures(ArcGIS.Core.Data.FeatureClass%2cSystem.Double%2cArcGIS.Core.Data.LinearReferencing.EventTableConfiguration)" data-throw-if-not-resolved="false"></xref></p>


### LocatingErrorType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.LocatingErrorType.yml" sourcestartlinenumber="1">Specifies the error type associated with a row in the event table when determining the event's location along a route via the dynamic
segmentation process.</p>


### PointEventInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventInfo.yml" sourcestartlinenumber="1">Represents information for an event table with point events. Each row in the table references an event, and its location is expressed as
measurements along a route feature.</p>


### PointEventSourceOptions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventSourceOptions.yml" sourcestartlinenumber="1">Represents a configuration to create a dynamic feature class (<xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>) originating from point events using the dynamic
segmentation process.</p>


### PointEventTableConfiguration

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.PointEventTableConfiguration.yml" sourcestartlinenumber="1">Describes a point event table to hold events' information as the results of <xref href="ArcGIS.Core.Data.LinearReferencing.RouteInfo.LocateFeatures(ArcGIS.Core.Data.FeatureClass%2cSystem.Double%2cArcGIS.Core.Data.LinearReferencing.EventTableConfiguration)" data-throw-if-not-resolved="false"></xref></p>


### RouteEventSource

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteEventSource.yml" sourcestartlinenumber="1">Represents a dynamic feature class created through the dynamic segmentation process.</p>


### RouteEventSourceDefinition

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteEventSourceDefinition.yml" sourcestartlinenumber="1">Represents the schema and properties of an <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>.</p>


### RouteEventSourceError

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteEventSourceError.yml" sourcestartlinenumber="1">Represents an error when locating an event along a route during <xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref> creation or update, which uses a dynamic
segmentation process.</p>


### RouteEventSourceOptions

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteEventSourceOptions.yml" sourcestartlinenumber="1">Provides a configuration to create a dynamic feature class (<xref href="ArcGIS.Core.Data.LinearReferencing.RouteEventSource" data-throw-if-not-resolved="false"></xref>) using the dynamic segmentation process.</p>


### RouteInfo

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.LinearReferencing.RouteInfo.yml" sourcestartlinenumber="1">Represents a route feature class's information, <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>. A route feature class is an M-enabled
polyline feature class containing a unique identifier attribute field.</p>




