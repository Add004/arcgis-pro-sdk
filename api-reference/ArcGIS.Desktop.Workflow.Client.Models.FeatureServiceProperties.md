# FeatureServiceProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.html">Workflow</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.html">Client</a>.<a class="xref" href="ArcGIS.Desktop.Workflow.Client.Models.html">Models</a>
- Assembly: ArcGIS.Desktop.Workflow.Client.dll

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Feature service properties for an extended or related property table.</p>


## Object Signature

```csharp
public class FeatureServiceProperties
```


## Members

### FeatureServiceProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Feature service properties for an extended or related property table.</p>


```csharp
public FeatureServiceProperties()
```
### FeatureServiceUniqueId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">The field name in the feature service to use as the unique Id.</p>


```csharp
public string FeatureServiceUniqueId { get; }
```
### ItemId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Portal item id of the feature service.</p>


```csharp
public string ItemId { get; }
```
### ItemType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Specific item type for the feature service. If not specified, the default is a standard feature service.</p>


```csharp
public ItemType ItemType { get; }
```
### LayerId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Layer id of the feature service.</p>


```csharp
public string LayerId { get; }
```
### PortalType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Portal where the portal item is stored. If not specified, the default is Current.</p>


```csharp
public PortalType? PortalType { get; }
```
### PortalUrl

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Specific portal url where the item is stored. This is only required when portalType == 'Other'.</p>


```csharp
public string PortalUrl { get; }
```
### Secure

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Workflow.Client.Models.FeatureServiceProperties.yml" sourcestartlinenumber="1">Indicates whether a service is secure. Currently only items with PortalType == 'Current' can be secured.</p>


```csharp
public bool? Secure { get; }
```


