# ArcGIS.Core.Data.PluginDatastore

- Type: namespace
- Assembly: ArcGIS.Core.dll




## Members

### PluginCursorTemplate

- Kind: class

<p>
    This abstract class serves as one of the key extensibility points that comprise the <i>Plugin Datastore Framework</i>.
    Specifically, each instance of concrete class that implements this abstraction acts as a conduit between
    a cursor traversing a data structure in a third-party data source and a <xref href="ArcGIS.Core.Data.RowCursor" data-throw-if-not-resolved="false"></xref> object in ArcGIS Pro.
    </p>


### PluginDatasourceConnectionPath

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatasourceConnectionPath.yml" sourcestartlinenumber="1">Represents the identification of a data source made available to ArcGIS Pro via a plug-in data source add-in.</p>


### PluginDatasourceTemplate

- Kind: class

<p>
    This abstract class serves as one of the key extensibility points that comprise the <i>Plugin Datastore Framework</i>.
    Specifically, each instance of a concrete class that implements this abstraction acts as a conduit between
    a third-party data source and ArcGIS Pro via the deployment of a plug-in data source add-in.
    </p>
<p>
    Currently, the framework only supports <xref href="ArcGIS.Core.Data.DatasetType.Table" data-throw-if-not-resolved="false"></xref>s and 
    <xref href="ArcGIS.Core.Data.DatasetType.FeatureClass" data-throw-if-not-resolved="false"></xref>s in a read-only manner.
    </p>


### PluginDatastore

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginDatastore.yml" sourcestartlinenumber="1">Represents a plug-in data store that makes a third-party data format accessible to ArcGIS Pro, albeit in a read-only manner.</p>


### PluginField

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginField.yml" sourcestartlinenumber="1">Represents a column in a plug-in table or feature class.</p>


### PluginRow

- Kind: class

<p sourcefile="api/ArcGIS.Core.Data.PluginDatastore.PluginRow.yml" sourcestartlinenumber="1">Represents a row in a plug-in table.</p>


### PluginTableTemplate

- Kind: class

<p>
    This abstract class serves as one of the key extensibility points that comprise the <i>Plugin Datastore Framework</i>.
    Specifically, each instance of concrete class that implements this abstraction acts as a conduit between
    a data structure in a third-party data source and a <xref href="ArcGIS.Core.Data.Table" data-throw-if-not-resolved="false"></xref> (or <xref href="ArcGIS.Core.Data.FeatureClass" data-throw-if-not-resolved="false"></xref>) in ArcGIS Pro.
    </p>
<p>
    A plug-in table does not necessarily correspond to a database table on the back end. It can be any data structure or format, but it <i>presented</i> to ArcGIS as a table.
    </p>
<p>
    If the list of <xref href="ArcGIS.Core.Data.PluginDatastore.PluginField" data-throw-if-not-resolved="false"></xref>s returned by <xref href="ArcGIS.Core.Data.PluginDatastore.PluginTableTemplate.GetFields" data-throw-if-not-resolved="false"></xref> has a field whose type is <xref href="ArcGIS.Core.Data.FieldType.Geometry" data-throw-if-not-resolved="false"></xref>, 
    then this concrete implementation is considered a feature class; otherwise, a table.
    </p>




