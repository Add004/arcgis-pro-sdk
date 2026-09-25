# CIMBASuitabilityAnalysisTargetSiteSubLayer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis target site layer.</p>


## Object Signature

```csharp
public class CIMBASuitabilityAnalysisTargetSiteSubLayer : CIMBASuitabilityAnalysisSubLayer, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMBASuitabilityAnalysisTargetSiteSubLayer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Represents a Business Analyst Suitability Analysis target site layer.</p>


```csharp
public CIMBASuitabilityAnalysisTargetSiteSubLayer()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Creates a deep copy of CIMBASuitabilityAnalysisTargetSiteSubLayer.</p>


```csharp
public CIMBASuitabilityAnalysisTargetSiteSubLayer Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Reconstructs the CIMBASuitabilityAnalysisTargetSiteSubLayer with a specified state from a JSON encoding.</p>


```csharp
public static CIMBASuitabilityAnalysisTargetSiteSubLayer FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SelectedSourceTargetSiteObjectID

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Gets or sets the object ID of the Suitability Analysis target site.</p>


```csharp
public string SelectedSourceTargetSiteObjectID { get; set; }
```
### SourceTargetSiteDataConnection

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Gets or sets the Suitability Analysis target site data connection.</p>


```csharp
public CIMStandardDataConnection SourceTargetSiteDataConnection { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMBASuitabilityAnalysisTargetSiteSubLayer and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMBASuitabilityAnalysisTargetSiteSubLayer.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


