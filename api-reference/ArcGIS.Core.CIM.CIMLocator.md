# CIMLocator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Represents properties of locator for the map.</p>


## Object Signature

```csharp
public class CIMLocator : CIMObject, INotifyPropertyChanged, IXmlSerializable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Locator stores the properties for a locator in a map.</p>


## Members

### CIMLocator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Represents properties of locator for the map.</p>


```csharp
public CIMLocator()
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Creates a deep copy of CIMLocator.</p>


```csharp
public CIMLocator Clone()
```
### Enabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to this locator is enabled.</p>


```csharp
public bool Enabled { get; set; }
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Reconstructs the CIMLocator with a specified state from a JSON encoding.</p>


```csharp
public static CIMLocator FromJson(string json, JsonDeserializationSettings settings = null)
```
### LocatorType

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Gets or sets the type of locator for the LocatorURI specified.</p>


```csharp
public LocatorType LocatorType { get; set; }
```
### LocatorURI

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Gets or sets locator source URI. It can either be a local path, URL or a layer URI from this map. e.g. file://&lt;folder_path&gt;,  http://&lt;url&gt;, CIMPATH=&lt;cim_layer_UR&gt;.</p>


```csharp
public string LocatorURI { get; set; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Gets or sets the name of the locator.</p>


```csharp
public string Name { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### SuggestionsEnabled

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether or not to suggestions should enabled if the locator supports suggestions.</p>


```csharp
public bool SuggestionsEnabled { get; set; }
```
### SuggestionsSupported

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether the locator supports suggestions.</p>


```csharp
public bool SuggestionsSupported { get; set; }
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMLocator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMLocator.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


