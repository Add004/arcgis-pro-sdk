# KGDurativeEventMissingOneTimeBehaviour

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventMissingOneTimeBehaviour.yml" sourcestartlinenumber="1">Defines the behaviour when a durative event has a missing start or end time.</p>


## Object Signature

```csharp
public enum KGDurativeEventMissingOneTimeBehaviour
```


## Members

### Error

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventMissingOneTimeBehaviour.yml" sourcestartlinenumber="1">Return an error.</p>


```csharp
Error = 0
```
### Exclude

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventMissingOneTimeBehaviour.yml" sourcestartlinenumber="1">Do not use the event in a path.</p>


```csharp
Exclude = 1
```
### MakeNonEvent

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventMissingOneTimeBehaviour.yml" sourcestartlinenumber="1">Consider the entity or relationship is not an event.</p>


```csharp
MakeNonEvent = 2
```
### MakePunctualEvent

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventMissingOneTimeBehaviour.yml" sourcestartlinenumber="1">Convert the durative event to a punctual event at the known time.</p>


```csharp
MakePunctualEvent = 3
```


