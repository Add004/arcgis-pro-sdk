# CodedValueDomain

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.CodedValueDomain.yml" sourcestartlinenumber="1">Represents the information about the valid coded values belonging to this coded value domain.</p>


## Object Signature

```csharp
public sealed class CodedValueDomain : Domain, IDisposable
```

## Remarks

<p sourcefile="api/ArcGIS.Core.Data.CodedValueDomain.yml" sourcestartlinenumber="1">A CodedValueDomain maintains the information about the valid coded values belonging to this coded value domain.
Domains may be assigned to a field at the table level or if the table has subtypes, they would be assigned at the subtype level.
A domain indicates the valid values for a field, and will indicate during validation if the field value is outside of this valid list.</p>


## Members

### GetCodedValue(string)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CodedValueDomain.yml" sourcestartlinenumber="1">Gets the coded value that matches the given name.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public object GetCodedValue(string name)
```
### GetCodedValuePairs()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CodedValueDomain.yml" sourcestartlinenumber="1">Gets a SortedList of the coded values (value and name) maintained by this CodedValueDomain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public SortedList<object, string> GetCodedValuePairs()
```
### GetCount()

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CodedValueDomain.yml" sourcestartlinenumber="1">Gets the number of codes maintained by this CodedValueDomain.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public int GetCount()
```
### GetName(object)

- Kind: method

<p sourcefile="api/ArcGIS.Core.Data.CodedValueDomain.yml" sourcestartlinenumber="1">Gets the name of a given coded value.
This method must be called on the MCT. Use QueuedTask.Run.</p>


```csharp
public string GetName(object value)
```


