# DatabaseConnectionProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">Represents the properties used to connect to an enterprise database or geodatabase.</p>


## Object Signature

```csharp
public sealed class DatabaseConnectionProperties : Connector
```


## Members

### DatabaseConnectionProperties(EnterpriseDatabaseType)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">The constructor.</p>


```csharp
public DatabaseConnectionProperties(EnterpriseDatabaseType databaseManagementSystemType)
```
### AuthenticationMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">If “AUTHENTICATION_MODE” is “OSA” then “USER” and “PASSWORD” are not required. “OSA” represents operating system authentication and
uses the operating system credentials to establish a connection with the database.</p>


```csharp
public AuthenticationMode AuthenticationMode { get; set; }
```
### Branch

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">A multi-branch version to connect to.  Acceptable value is a string that represents a multi-branch version name.</p>


```csharp
public string Branch { get; set; }
```
### DBMS

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">The type of database client.</p>


```csharp
public EnterpriseDatabaseType DBMS { get; }
```
### Database

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">The database connected to.</p>


```csharp
public string Database { get; set; }
```
### Instance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">The instance of the database connected to.</p>


```csharp
public string Instance { get; set; }
```
### Password

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">Connected password.</p>


```csharp
public string Password { get; set; }
```
### ProjectInstance

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">The instance of the database connected to.  Internally, it is used for Oracle only.</p>


```csharp
public string ProjectInstance { get; set; }
```
### User

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">Connected user.</p>


```csharp
public string User { get; set; }
```
### Version

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.DatabaseConnectionProperties.yml" sourcestartlinenumber="1">A traditional version to connect to.  Acceptable value is a string that represents a traditional version name.</p>


```csharp
public string Version { get; set; }
```


