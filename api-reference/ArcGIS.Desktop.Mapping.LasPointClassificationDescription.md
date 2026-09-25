# LasPointClassificationDescription

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="1">Represents an edit to be performed on a set of LAS points.</p>
<p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="5">Set the <xref href="ArcGIS.Desktop.Mapping.LasPointClassificationDescription.ClassCode" data-throw-if-not-resolved="false"></xref> to assign a classification code to the LAS points.
Set or clear the flag values to update the classification flags on the LAS points.</p>
<p></p>


## Object Signature

```csharp
public class LasPointClassificationDescription
```


## Members

### LasPointClassificationDescription()

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="1">Creates a new instance of a <xref href="ArcGIS.Desktop.Mapping.LasPointClassificationDescription" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasPointClassificationDescription()
```
### ClassCode

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="1">Gets and sets the classification code to assign.  The default value is -1 meaning that no classification
code will be applied to the identified LAS points.</p>


```csharp
public int ClassCode { get; set; }
```
### KeyPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="1">Gets and sets the key points edit flag to assign.  The default value is <xref href="ArcGIS.Desktop.Mapping.LasClassFlagEditType.NoChange" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasClassFlagEditType KeyPoints { get; set; }
```
### OverlapPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="1">Gets and sets the overlap points edit flag to assign. The default value is <xref href="ArcGIS.Desktop.Mapping.LasClassFlagEditType.NoChange" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasClassFlagEditType OverlapPoints { get; set; }
```
### SyntheticPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="1">Gets and sets the synthetic points edit flag to assign.  The default value is <xref href="ArcGIS.Desktop.Mapping.LasClassFlagEditType.NoChange" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasClassFlagEditType SyntheticPoints { get; set; }
```
### WithheldPoints

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.LasPointClassificationDescription.yml" sourcestartlinenumber="1">Gets and sets the withheld points edit flag to assign. The default value is <xref href="ArcGIS.Desktop.Mapping.LasClassFlagEditType.NoChange" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public LasClassFlagEditType WithheldPoints { get; set; }
```


