# Serializer

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.Serializer.yml" sourcestartlinenumber="1">Provides static methods that can be used for JSON and XML serialization and deserialization.</p>


## Object Signature

```csharp
public sealed class Serializer
```


## Members

### Serializer()

- Kind: constructor

<p sourcefile="api/ArcGIS.Core.CIM.Serializer.yml" sourcestartlinenumber="1">Provides static methods that can be used for JSON and XML serialization and deserialization.</p>


```csharp
public Serializer()
```
### UpgradeJSON(string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.Serializer.yml" sourcestartlinenumber="1">Upgrades input CIM JSON string from source version to the latest version. Strings serialized using Core objects should be upgraded to current version for them to be succussfully deserialized.</p>


```csharp
public static string UpgradeJSON(string sourceVersion, string inputJson)
```


