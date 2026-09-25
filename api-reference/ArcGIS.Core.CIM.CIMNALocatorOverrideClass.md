# CIMNALocatorOverrideClass

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Represents locator settings for a particular class.</p>


## Object Signature

```csharp
public class CIMNALocatorOverrideClass : CIMObject, INotifyPropertyChanged, IXmlSerializable
```


## Members

### CIMNALocatorOverrideClass()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Represents locator settings for a particular class.</p>


```csharp
public CIMNALocatorOverrideClass()
```
### ClassName

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Gets or sets the NAClass name for the locator settings.</p>


```csharp
public string ClassName { get; set; }
```
### Clone()

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Creates a deep copy of CIMNALocatorOverrideClass.</p>


```csharp
public CIMNALocatorOverrideClass Clone()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Reconstructs the CIMNALocatorOverrideClass with a specified state from a JSON encoding.</p>


```csharp
public static CIMNALocatorOverrideClass FromJson(string json, JsonDeserializationSettings settings = null)
```
### Locator

- Kind: property

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Gets or sets the locator.</p>


```csharp
public NALocatorDefinition Locator { get; set; }
```
### ReadXmlElement(XmlReader)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Reads the child element inside the reader.</p>


```csharp
protected override bool ReadXmlElement(XmlReader reader)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Creates a JSON encoding of the CIMNALocatorOverrideClass and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```
### WriteXmlElements(XmlWriter)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.CIMNALocatorOverrideClass.yml" sourcestartlinenumber="1">Writes a child element to the writer.</p>


```csharp
protected override void WriteXmlElements(XmlWriter writer)
```


