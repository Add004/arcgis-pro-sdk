# CIMGeotriggerNotificationProperties

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Represents a geotrigger notification properties.</p>


## Object Signature

```csharp
public class CIMGeotriggerNotificationProperties : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMGeotriggerNotificationProperties()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Represents a geotrigger notification properties.</p>


```csharp
public CIMGeotriggerNotificationProperties()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Creates a deep copy of CIMGeotriggerNotificationProperties.</p>


```csharp
public CIMGeotriggerNotificationProperties Clone()
```
### ExpressionInfo

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Gets or sets the arcade expression which can be used to configure notification information when the Geotrigger condition is met. The expression uses the Geotrigger Notification Arcade profile.</p>


```csharp
public CIMExpressionInfo ExpressionInfo { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Reconstructs the CIMGeotriggerNotificationProperties with a specified state from a JSON encoding.</p>


```csharp
public static CIMGeotriggerNotificationProperties FromJson(string json, JsonDeserializationSettings settings = null)
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### RequestedActions

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Gets or sets list of recommended actions that the author intends to be taken for this Geotrigger. Actions can be any strings that are supported by geotrigger enabled apps in your organization and should cover all possible 'action' values returned from evaluation of expressionInfo.expression.</p>


```csharp
public string[] RequestedActions { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMGeotriggerNotificationProperties and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMGeotriggerNotificationProperties.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


