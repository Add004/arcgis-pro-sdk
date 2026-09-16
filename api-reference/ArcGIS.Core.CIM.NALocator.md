# NALocator

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.NALocator.yml" sourcestartlinenumber="1">Represent a network analyst locator. This class is reserved for esri internal use only.</p>


## Object Signature

```csharp
public sealed class NALocator : NALocatorDefinition, INotifyPropertyChanged, IXmlSerializable
```


## Members

### NALocator()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.NALocator.yml" sourcestartlinenumber="1">Represent a network analyst locator. This class is reserved for esri internal use only.</p>


```csharp
public NALocator()
```
### FromJson(string, JsonDeserializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocator.yml" sourcestartlinenumber="1">Reconstructs the NALocator with a specified state from a JSON encoding.</p>


```csharp
public static NALocator FromJson(string json, JsonDeserializationSettings settings = null)
```
### ToJson(JsonSerializationSettings)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.NALocator.yml" sourcestartlinenumber="1">Creates a JSON encoding of the NALocator and its current state.</p>


```csharp
public override string ToJson(JsonSerializationSettings settings = null)
```


