# FeatureExpirationMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.FeatureExpirationMethod.yml" sourcestartlinenumber="1">Stream service feature expiration method.</p>


## Object Signature

```csharp
public enum FeatureExpirationMethod
```


## Members

### MaximumFeatureAge

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FeatureExpirationMethod.yml" sourcestartlinenumber="1">Features will expire after the specified time since the beginning of their lifetime.</p>


```csharp
MaximumFeatureAge = 1
```
### MaximumFeatureCount

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.FeatureExpirationMethod.yml" sourcestartlinenumber="1">The oldest features will expire after a threshold number of features has been reached.</p>


```csharp
MaximumFeatureCount = 0
```


