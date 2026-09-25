# ValidationDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Topology.html">Topology</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Topology.ValidationDescription.yml" sourcestartlinenumber="1">Represents a mechanism to validate a <xref href="ArcGIS.Core.Data.Topology.Topology" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class ValidationDescription
```


## Members

### ValidationDescription(Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.Data.Topology.ValidationDescription.yml" sourcestartlinenumber="1">Initializes a new instance of the <code>ValidationDescription</code> class.</p>


```csharp
public ValidationDescription(Envelope extent)
```
### Extent

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.ValidationDescription.yml" sourcestartlinenumber="1">Gets the area of interest for which the topology is to be validated.</p>


```csharp
public Envelope Extent { get; }
```
### ServiceSynchronizationType

- Kind: property

<p sourcefile="api/ArcGIS.Core.Data.Topology.ValidationDescription.yml" sourcestartlinenumber="1">Gets or sets the <xref href="ArcGIS.Core.Data.ServiceSynchronizationType" data-throw-if-not-resolved="false"></xref> for the <xref href="ArcGIS.Core.Data.Topology.Topology.Validate(ArcGIS.Core.Data.Topology.ValidationDescription)" data-throw-if-not-resolved="false"></xref> operation.
An optional value.  If not set, the default value is <xref href="ArcGIS.Core.Data.ServiceSynchronizationType.Asynchronous" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public ServiceSynchronizationType ServiceSynchronizationType { get; set; }
```


