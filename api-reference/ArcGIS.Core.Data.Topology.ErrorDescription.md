# ErrorDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.ErrorDescription.yml" sourcestartlinenumber="1">Represents a mechanism to retrieve <xref href="ArcGIS.Core.Data.Topology.TopologyError" data-throw-if-not-resolved="false"></xref> associated with a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ErrorDescription
```


## Members

### ErrorDescription(Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Topology.ErrorDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>ErrorDescription</code> class.</p>


```csharp
public ErrorDescription(Envelope extent)
```
### ErrorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.ErrorDescription.yml" sourcestartlinenumber="1">Gets or sets the type of <xref href="ArcGIS.Core.Data.Topology.TopologyError" data-throw-if-not-resolved="false"></xref> to be retrieved.  By default, the value is
<xref href="ArcGIS.Core.Data.Topology.ErrorType.ErrorAndException" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ErrorType ErrorType { get; set; }
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.ErrorDescription.yml" sourcestartlinenumber="1">Gets the area of interest from which <xref href="ArcGIS.Core.Data.Topology.TopologyError" data-throw-if-not-resolved="false"></xref>s are to be retrieved.</p>


```csharp
public Envelope Extent { get; }
```
### TopologyRule

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.ErrorDescription.yml" sourcestartlinenumber="1">Gets or sets the type of <xref href="ArcGIS.Core.Data.Topology.TopologyRule" data-throw-if-not-resolved="false"></xref> against which features are
violating within a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public TopologyRule TopologyRule { get; set; }
```


