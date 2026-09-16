# Terminal

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.UtilityNetwork.html">UtilityNetwork</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Represents a single terminal on a junction feature.</p>


## Object Signature

```csharp
public sealed class Terminal : IEquatable<Terminal>
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Terminal objects can be obtained by calling <xref href="ArcGIS.Core.Data.UtilityNetwork.TerminalConfiguration.Terminals" data-throw-if-not-resolved="false"></xref>.</p>


## Members

### Equals(Terminal)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public bool Equals(Terminal other)
```
### Equals(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Determines if the given object is identical to this object.</p>


```csharp
public override bool Equals(object obj)
```
### GetHashCode()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Obtains a hash code of the object.  Used in Equals.</p>


```csharp
public override int GetHashCode()
```
### ID

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Gets a numeric ID that identifies this terminal.</p>


```csharp
public int ID { get; }
```
### IsUpstreamTerminal

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Returns whether this terminal is on the upstream side of the device</p>


```csharp
public bool IsUpstreamTerminal { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Gets a user-readable string that describes this terminal.</p>


```csharp
public string Name { get; }
```
### operator ==(Terminal, Terminal)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">thisTerminal</code> and <code class="paramref">otherTerminal</code> are equal.</p>


```csharp
public static bool operator ==(Terminal thisTerminal, Terminal otherTerminal)
```
### operator !=(Terminal, Terminal)

- Kind: operator

<p sourcefile="api/ArcGIS.Core.Data.UtilityNetwork.Terminal.yml" sourcestartlinenumber="1">Returns true if <code class="paramref">thisTerminal</code> and <code class="paramref">otherTerminal</code> are not equal.</p>


```csharp
public static bool operator !=(Terminal thisTerminal, Terminal otherTerminal)
```


