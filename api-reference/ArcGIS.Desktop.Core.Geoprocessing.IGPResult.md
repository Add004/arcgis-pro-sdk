# IGPResult

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Geoprocessing.html">Geoprocessing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">Geoprocessing tool result object returned by <xref href="ArcGIS.Desktop.Core.Geoprocessing.Geoprocessing.ExecuteToolAsync(System.String%2cSystem.Collections.Generic.IEnumerable%7bSystem.String%7d%2cSystem.Collections.Generic.IEnumerable%7bSystem.Collections.Generic.KeyValuePair%7bSystem.String%2cSystem.String%7d%7d%2cArcGIS.Desktop.Framework.Threading.Tasks.CancelableProgressor%2cArcGIS.Desktop.Core.Geoprocessing.GPExecuteToolFlags)" data-throw-if-not-resolved="false"></xref></p>


## Object Signature

```csharp
public interface IGPResult
```


## Members

### Environments

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">Geoprocessing environments used locally in tool execution.</p>
<ul><li>Tuple.Item1 - name</li><li>Tuple.Item2 - datatype</li><li>Tuple.Item3 - value</li></ul>


```csharp
IEnumerable<Tuple<string, string, string>> Environments { get; }
```
### ErrorCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">Error code for tool execution result:</p>
<ul><li>0 : Success (tool executed without any error)</li><li>not 0 : Tool failed or was canceled.</li></ul>


```csharp
int ErrorCode { get; }
```
### ErrorMessages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">Returns error messages - see code example below:</p>


```csharp
IEnumerable<IGPMessage> ErrorMessages { get; }
```
### HasWarnings

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">True if tool executed with any warning.</p>


```csharp
bool HasWarnings { get; }
```
### IsCanceled

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">True if tool execution is canceled before it finishes.</p>


```csharp
bool IsCanceled { get; }
```
### IsFailed

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">True when tool fails or canceled.</p>


```csharp
bool IsFailed { get; }
```
### Messages

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">All output messages.
To filter only one type of messages use GPMessageType (Warning, Error) - see code example below.</p>


```csharp
IEnumerable<IGPMessage> Messages { get; }
```
### Parameters

- Kind: property

<ul><li>Tuple.Item1 - name</li><li>Tuple.Item2 - datatype</li><li>Tuple.Item3 - value</li><li>Tuple.Item4 - input = true, output = false</li></ul>


```csharp
IEnumerable<Tuple<string, string, string, bool>> Parameters { get; }
```
### ReturnValue

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">Returns execution result value as a string or null if tool execution fails.</p>


```csharp
string ReturnValue { get; }
```
### ValueTypes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">Data types of output values, null if tool fails.</p>


```csharp
IReadOnlyList<string> ValueTypes { get; }
```
### Values

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Geoprocessing.IGPResult.yml" sourcestartlinenumber="1">Output values, null if tool execution fails.</p>


```csharp
IReadOnlyList<string> Values { get; }
```


