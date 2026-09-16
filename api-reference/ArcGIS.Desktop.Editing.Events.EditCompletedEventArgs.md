# EditCompletedEventArgs

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Editing.html">Editing</a>.<a class="xref" href="ArcGIS.Desktop.Editing.Events.html">Events</a>
- Assembly: ArcGIS.Desktop.Editing.dll

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Provides information about the changes that were made by a recently completed <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


## Object Signature

```csharp
public sealed class EditCompletedEventArgs
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">The delegate that you provide when subscribing, will receive an EditCompletedEventArgs from which your delegate can find information about the changes made.</p>


## Members

### CompletedType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the type of this event.</p>


```csharp
public EditCompletedType CompletedType { get; }
```
### Creates

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the collection of feature IDs that were created by the <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SelectionSet Creates { get; }
```
### Deletes

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the collection of feature IDs that were deleted by the <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SelectionSet Deletes { get; }
```
### EventToken

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the optional token that may have been set in the original <xref href="ArcGIS.Desktop.Editing.EditOperation.EventToken?text=EditOperation.EventToken" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public object EventToken { get; }
```
### FeatureChanged(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether any change has been made to a particular feature within the given MapMember.</p>


```csharp
public bool FeatureChanged(MapMember member, long oid)
```
### FeatureDeleted(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether a particular feature has been deleted from the given MapMember.</p>


```csharp
public bool? FeatureDeleted(MapMember member, long oid)
```
### FeatureModified(MapMember, long)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether a particular feature has been modified within the given MapMember.</p>


```csharp
public bool FeatureModified(MapMember member, long oid)
```
### FeaturesChanged(MapMember, IEnumerable&lt;long&gt;)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether any one of the specified features has been changed within the given MapMember.</p>


```csharp
public bool FeaturesChanged(MapMember member, IEnumerable<long> oids)
```
### FeaturesCreated(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether any feature has been created within the given MapMember.</p>


```csharp
public bool FeaturesCreated(MapMember member)
```
### FeaturesDeleted(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether any feature has been deleted from the given MapMember.</p>


```csharp
public bool? FeaturesDeleted(MapMember member)
```
### FeaturesModified(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether any feature has been modified within the given MapMember.</p>


```csharp
public bool FeaturesModified(MapMember member)
```
### InvalidateAllMembers

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the collection of MapMembers for which no specific information is available,
other than, that features have changed in some way.</p>


```csharp
public IReadOnlyCollection<MapMember> InvalidateAllMembers { get; }
```
### Invalidated

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether the MapMember features have been changed dramatically by the <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public bool Invalidated { get; }
```
### MapMemberChanged(MapMember)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets whether a change has been made to any features within the given MapMember.</p>


```csharp
public bool MapMemberChanged(MapMember member)
```
### Members

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the collection of MapMembers for which information may be available.</p>


```csharp
public IReadOnlyCollection<MapMember> Members { get; }
```
### Modifies

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Editing.Events.EditCompletedEventArgs.yml" sourcestartlinenumber="1">Gets the collection of feature IDs that were modified by the <xref href="ArcGIS.Desktop.Editing.EditOperation?text=EditOperation" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public SelectionSet Modifies { get; }
```


