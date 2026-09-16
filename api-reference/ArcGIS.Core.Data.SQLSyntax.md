# SQLSyntax

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Represents the gateway to access information about the SQL syntax and other functionality supported by a given <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>,
such as the delimiting character used in qualifying table and field names, and the identifier quote character.</p>


## Object Signature

```csharp
public sealed class SQLSyntax
```


## Members

### Format(DateOnly, SQLDateTimeType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Formats the <code class="paramref">dateOnly</code> value into a literal string in the format specified by <code class="paramref">dateTimeType</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Format(DateOnly dateOnly, SQLDateTimeType dateTimeType)
```
### Format(DateTime, SQLDateTimeType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Formats the <code class="paramref">dateTime</code> value into a literal string in the format specified by <code class="paramref">dateTimeType</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Format(DateTime dateTime, SQLDateTimeType dateTimeType)
```
### Format(DateTimeOffset, SQLDateTimeType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Formats the <code class="paramref">dateTimeOffset</code> value into a literal string in the format specified by <code class="paramref">dateTimeType</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Format(DateTimeOffset dateTimeOffset, SQLDateTimeType dateTimeType)
```
### Format(TimeOnly, SQLDateTimeType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Formats the <code class="paramref">timeOnly</code> value into a literal string in the format specified by <code class="paramref">dateTimeType</code>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string Format(TimeOnly timeOnly, SQLDateTimeType dateTimeType)
```
### GetFunctionName(SQLFunction)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>-dependent SQL function name corresponding to <code class="paramref">sqlFunction</code>,
e.g., <xref href="ArcGIS.Core.Data.SQLFunction.Sum" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetFunctionName(SQLFunction sqlFunction)
```
### GetProperty(SQLProperty)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Gets the <b>boolean</b> property corresponding to <code class="paramref">sqlProperty</code>, e.g., <xref href="ArcGIS.Core.Data.SQLProperty.IsIdentifierCaseSensitive" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public bool GetProperty(SQLProperty sqlProperty)
```
### GetSpecialCharacter(SQLSpecialCharacter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Gets the <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>-dependent SQL special character corresponding to <code class="paramref">sqlSpecialCharacter</code>,
e.g., <xref href="ArcGIS.Core.Data.SQLSpecialCharacter.WildcardManyMatch" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetSpecialCharacter(SQLSpecialCharacter sqlSpecialCharacter)
```
### GetSupportedClauses()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.SQLClause" data-throw-if-not-resolved="false"></xref> supported by a given <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<SQLClause> GetSupportedClauses()
```
### GetSupportedPredicates()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Gets the list of <xref href="ArcGIS.Core.Data.SQLPredicate" data-throw-if-not-resolved="false"></xref> supported by a given <xref href="ArcGIS.Core.Data.Datastore" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<SQLPredicate> GetSupportedPredicates()
```
### GetSupportedStrings(SQLStringType)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Gets all of the supported strings corresponding to <code class="paramref">sqlStringType</code>, e.g., <xref href="ArcGIS.Core.Data.SQLStringType.InvalidCharacters" data-throw-if-not-resolved="false"></xref>.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public IReadOnlyList<string> GetSupportedStrings(SQLStringType sqlStringType)
```
### ParseColumnName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Given a column name (fully qualified or otherwise), determines its qualification parts.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<string, string, string, string> ParseColumnName(string columnFullName)
```
### ParseTableName(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Given a table name (fully qualified or otherwise), determines its qualification parts.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public Tuple<string, string, string> ParseTableName(string tableFullName)
```
### QualifyColumnName(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Given a table name and column name, returns its fully qualified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string QualifyColumnName(string tableName, string columnName)
```
### QualifyTableName(string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.SQLSyntax.yml" sourcestartlinenumber="1">Given a database name, owner name and table name, returns its fully qualified name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string QualifyTableName(string databaseName, string ownerName, string tableName)
```


