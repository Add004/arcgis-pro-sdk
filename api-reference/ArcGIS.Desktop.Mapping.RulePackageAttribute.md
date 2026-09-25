# RulePackageAttribute

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="1">Represents a rule package attribute and any associated annotations.</p>


## Object Signature

```csharp
public sealed class RulePackageAttribute
```

## Remarks

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="1">A rule package attribute instance contains its name, value, and type along with a collection of any associated
<xref href="ArcGIS.Desktop.Mapping.RulePackageAttribute.Annotations" data-throw-if-not-resolved="false"></xref> read from the City Engine rule file (please see below).<br>
Note: CGA annotations can be referenced here: <a href="http://cehelp.esri.com/help/index.jsp?topic=/com.procedural.cityengine.help/html/cgareference/cga_annotations.html"></a><p></p><p></p>
<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="5">Notes on Annotations:<br><b><xref href="Angle" data-throw-if-not-resolved="False" data-raw-source="@Angle" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="5"></xref>, <xref href="Color" data-throw-if-not-resolved="False" data-raw-source="@Color" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="5"></xref>, <xref href="Distance" data-throw-if-not-resolved="False" data-raw-source="@Distance" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="5"></xref>, <xref href="Percent" data-throw-if-not-resolved="False" data-raw-source="@Percent" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="5"></xref></b><br>
If present in the collection, they have no value
<b><xref href="Hidden" data-throw-if-not-resolved="False" data-raw-source="@Hidden" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="7"></xref></b><br>
Attributes annotated with <xref href="Hidden" data-throw-if-not-resolved="False" data-raw-source="@Hidden" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="8"></xref> are not retrieved from the Rule Package.
<br><b><xref href="File" data-throw-if-not-resolved="False" data-raw-source="@File" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="9"></xref> and <xref href="Directory" data-throw-if-not-resolved="False" data-raw-source="@Directory" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="9"></xref></b><br>
Attributes annotated with <xref href="File" data-throw-if-not-resolved="False" data-raw-source="@File" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="10"></xref> or <xref href="Directory" data-throw-if-not-resolved="False" data-raw-source="@Directory" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="10"></xref> are not retrieved from the Rule Package. They are not supported for renderers.
<b><xref href="Handle" data-throw-if-not-resolved="False" data-raw-source="@Handle" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="11"></xref></b><br>
<xref href="Handle" data-throw-if-not-resolved="False" data-raw-source="@Handle" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="12"></xref> is not retrieved.
<b><xref href="In" data-throw-if-not-resolved="False" data-raw-source="@In" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="13"></xref> and <xref href="Out" data-throw-if-not-resolved="False" data-raw-source="@Out" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="13"></xref></b><br>
<xref href="In" data-throw-if-not-resolved="False" data-raw-source="@In" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="14"></xref> and <xref href="Out" data-throw-if-not-resolved="False" data-raw-source="@Out" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="14"></xref> are not retrieved. <xref href="In" data-throw-if-not-resolved="False" data-raw-source="@In" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="14"></xref> is reflected in the <xref href="ArcGIS.Desktop.Mapping.RulePackageDescription.GeometryType" data-throw-if-not-resolved="false"></xref>. An
<xref href="Out" data-throw-if-not-resolved="False" data-raw-source="@Out" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="15"></xref> is implicitly always combinedShape. A value of separatedShapes for <xref href="Out" data-throw-if-not-resolved="False" data-raw-source="@Out" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="15"></xref> is not supported.
<b><xref href="Group" data-throw-if-not-resolved="False" data-raw-source="@Group" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="16"></xref> with index</b><br>
When an order index is added to a <xref href="Group" data-throw-if-not-resolved="False" data-raw-source="@Group" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="17"></xref> ~that~ group order index is added as a GroupOrder key/value.
<br><b><xref href="Range" data-throw-if-not-resolved="False" data-raw-source="@Range" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="18"></xref></b><br>
<xref href="Ranges" data-throw-if-not-resolved="False" data-raw-source="@Ranges" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="19"></xref> can be numeric or a domain of specific values. Check the RangeType key. It will be
one of &quot;Range | Domain&quot;.
<br><b><xref href="StartRule" data-throw-if-not-resolved="False" data-raw-source="@StartRule" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="21"></xref></b><br>
<xref href="StartRule" data-throw-if-not-resolved="False" data-raw-source="@StartRule" sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="22"></xref> is not retrieved.
<br>
Annotation keys:</p>
<ul><li>Angle : if present indicates attribute was annotated with @Angle. No value (empty string)</li><li>Color : if present indicates attribute was annotated with @Color. No value (empty string)</li><li>Distance : if present indicates attribute was annotated with @Distance. No value (empty string)</li><li>Description : if present indicates attribute was annotated with @Description. The description, if any</li><li>Group : if present indicates attribute was annotated with @Group. A string containing the comma-separated group values</li><li>GroupOrder : if present indicates the @Group contained an index. An integer 0 or greater</li><li>Order : if present indicates attribute was annotated with @Order. An integer 0 or greater.</li><li>Percent: if present indicates attribute was annotated with @Percent. No value (empty string)</li><li>Range : if present indicates attribute was annotated with @Range. A string containing the comma-separated range values</li><li>RangeMin : if present indicates the @Range was numeric, RangeType = "Range". A double, the minimum range value</li><li>RangeMax : if present indicates the @Range was numeric, RangeType = "Range". A double, the maximum range value</li><li>RangeType : if present indicates the original @Range type. One of "Range | Domain"</li></ul>


## Members

### Annotations

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="1">Gets the collection of annotations associated with the attribute</p>


```csharp
public IReadOnlyDictionary<string, object> Annotations { get; }
```
### AttributeType

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="1">Gets the type of attribute value</p>


```csharp
public CGAAttributeType AttributeType { get; }
```
### Name

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="1">Gets the name of the attribute</p>


```csharp
public string Name { get; }
```
### Value

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Mapping.RulePackageAttribute.yml" sourcestartlinenumber="1">Gets the value of the attribute</p>


```csharp
public object Value { get; }
```


