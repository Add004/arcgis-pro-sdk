# IServerObjectExtension

- Type: interface
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Sharing.html">Sharing</a>
- Assembly: ArcGIS.Desktop.Core.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">This interface is used to implement support for external custom SOE,
and custom soe in an addin.</p>


## Object Signature

```csharp
public interface IServerObjectExtension
```


## Members

### GetSOEDisplayName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Gets the server object extension's display name</p>


```csharp
string GetSOEDisplayName()
```
### GetSOEInfos()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Gets the server object extension's infos</p>


```csharp
List<Tuple<string, string>> GetSOEInfos()
```
### GetSOEProps()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Gets the server object extension's props</p>


```csharp
List<Tuple<string, string>> GetSOEProps()
```
### GetSOEServiceType()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Gets the service type which the server object extension is applied for</p>


```csharp
string GetSOEServiceType()
```
### GetSOETypeName()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Gets the server object extension's type name</p>


```csharp
string GetSOETypeName()
```
### GetSOEWebCapabilities()

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Get the server object extension's web capabilities</p>


```csharp
string GetSOEWebCapabilities()
```
### SetSOEInfos(List&lt;Tuple&lt;string, string&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Sets the server object extension's infos</p>


```csharp
void SetSOEInfos(List<Tuple<string, string>> infos)
```
### SetSOEProps(List&lt;Tuple&lt;string, string&gt;&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Sets the server object extension's props</p>


```csharp
void SetSOEProps(List<Tuple<string, string>> props)
```
### SetSOEWebCapabilities(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Sharing.IServerObjectExtension.yml" sourcestartlinenumber="1">Set the server object extension's web capabilities</p>


```csharp
void SetSOEWebCapabilities(string capabilities)
```


