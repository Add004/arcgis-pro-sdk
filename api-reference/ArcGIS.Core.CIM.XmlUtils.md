# XmlUtils

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.XmlUtils.yml" sourcestartlinenumber="1">Contains a utility for reading a CIMObject from an XML string.</p>


## Object Signature

```csharp
public static class XmlUtils
```


## Members

### UpgradeAndDeserializeCIMObject(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.CIM.XmlUtils.yml" sourcestartlinenumber="1">Deserializes xml string and returns the CIMObject after upgrading the input xml.
This function can be used for reading existing XML strings, but subsequent serialization should be done in JSON.</p>


```csharp
public static CIMObject UpgradeAndDeserializeCIMObject(string inputXml)
```


