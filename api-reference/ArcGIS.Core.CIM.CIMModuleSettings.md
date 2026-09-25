# CIMModuleSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Represents module settings in the project.</p>


## Object Signature

```csharp
public class CIMModuleSettings : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMModuleSettings()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Represents module settings in the project.</p>


```csharp
public CIMModuleSettings()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Creates a deep copy of CIMModuleSettings.</p>


```csharp
public CIMModuleSettings Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Reconstructs the CIMModuleSettings with a specified state from a JSON encoding.</p>


```csharp
public static CIMModuleSettings FromJson(string json, JsonDeserializationSettings settings = null)
```
### ModuleName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Gets or sets the name of the module.</p>


```csharp
public string ModuleName { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SettingsXML

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Gets or sets module settings as XML.</p>


```csharp
public string SettingsXML { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMModuleSettings and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMModuleSettings.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


