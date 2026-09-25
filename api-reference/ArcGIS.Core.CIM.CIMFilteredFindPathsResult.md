# CIMFilteredFindPathsResult

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Represents results of a Filtered Find Paths search.</p>


## Object Signature

```csharp
public class CIMFilteredFindPathsResult : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMFilteredFindPathsResult()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Represents results of a Filtered Find Paths search.</p>


```csharp
public CIMFilteredFindPathsResult()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Creates a deep copy of CIMFilteredFindPathsResult.</p>


```csharp
public CIMFilteredFindPathsResult Clone()
```
### ConfigurationWarning

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Gets or sets the configuration warning.
When no path has been found, and the value is different from FFPConfigurationWarning.None,
it is likely that the user made an unintended mistake in the configuration.</p>


```csharp
public FFPConfigurationWarning ConfigurationWarning { get; set; }
```
### Error

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Gets or sets the error.
An error occurred if this object is not null.</p>


```csharp
public CIMFilteredFindPathsError Error { get; set; }
```
### ExecutionWarnings

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Gets or sets the execution warnings.</p>


```csharp
public FFPExecutionWarning[] ExecutionWarnings { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Reconstructs the CIMFilteredFindPathsResult with a specified state from a JSON encoding.</p>


```csharp
public static CIMFilteredFindPathsResult FromJson(string json, JsonDeserializationSettings settings = null)
```
### Paths

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Gets or sets the paths found by the Filtered Find Paths search.</p>


```csharp
public CIMKGPaths Paths { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### Statistics

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Gets or sets the statistics of the Filtered Find Paths search.</p>


```csharp
public CIMFilteredFindPathsStatistics Statistics { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMFilteredFindPathsResult and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMFilteredFindPathsResult.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


