# CIMNetworkTravelModeDefinitionContext

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Specifies the travel mode travel mode to be applied. Depending on the SourceType, some properties are conditionally required to indicate the travel mode.</p>


## Object Signature

```csharp
public class CIMNetworkTravelModeDefinitionContext : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNetworkTravelModeDefinitionContext()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Specifies the travel mode travel mode to be applied. Depending on the SourceType, some properties are conditionally required to indicate the travel mode.</p>


```csharp
public CIMNetworkTravelModeDefinitionContext()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNetworkTravelModeDefinitionContext.</p>


```csharp
public CIMNetworkTravelModeDefinitionContext Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Reconstructs the CIMNetworkTravelModeDefinitionContext with a specified state from a JSON encoding.</p>


```csharp
public static CIMNetworkTravelModeDefinitionContext FromJson(string json, JsonDeserializationSettings settings = null)
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Gets or sets the name.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SourceLayerURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Gets or sets the source Layer URI of the item. Set if sourced from another layer.</p>


```csharp
public string SourceLayerURI { get; set; }
```
### SourceType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Gets or sets the travel mode source type.</p>


```csharp
public NetworkTravelModeSourceType SourceType { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNetworkTravelModeDefinitionContext and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### TravelMode

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Gets or sets the travel mode. Required if not sourced from a named travel mode of a Network Dataset.</p>


```csharp
public CIMNetworkTravelModeDefinition TravelMode { get; set; }
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNetworkTravelModeDefinitionContext.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


