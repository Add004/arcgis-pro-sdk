# KGDurativeEventSwappedTimesBehaviour

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.CIM.html">CIM</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventSwappedTimesBehaviour.yml" sourcestartlinenumber="1">Defines the behaviour when a durative event start time is after the end time.</p>


## Object Signature

```csharp
public enum KGDurativeEventSwappedTimesBehaviour
```


## Members

### Error

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventSwappedTimesBehaviour.yml" sourcestartlinenumber="1">Return an error.</p>


```csharp
Error = 0
```
### Exclude

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventSwappedTimesBehaviour.yml" sourcestartlinenumber="1">Do not use the event in a path.</p>


```csharp
Exclude = 1
```
### MakeDurativeEvent

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventSwappedTimesBehaviour.yml" sourcestartlinenumber="1">Swap start and end time so that start time is before end time.</p>


```csharp
MakeDurativeEvent = 5
```
### MakeMaxPunctualEvent

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventSwappedTimesBehaviour.yml" sourcestartlinenumber="1">Convert the durative event to a punctual event at the maximum time.</p>


```csharp
MakeMaxPunctualEvent = 4
```
### MakeMinPunctualEvent

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventSwappedTimesBehaviour.yml" sourcestartlinenumber="1">Convert the durative event to a punctual event at the minimum time.</p>


```csharp
MakeMinPunctualEvent = 3
```
### MakeNonEvent

- Kind: field

<p sourcefile="api/ArcGIS.Core.CIM.KGDurativeEventSwappedTimesBehaviour.yml" sourcestartlinenumber="1">Consider the entity or relationship is not an event.</p>


```csharp
MakeNonEvent = 2
```


