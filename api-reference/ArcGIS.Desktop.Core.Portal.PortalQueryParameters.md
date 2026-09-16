# PortalQueryParameters

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Core.html">Core</a>.<a class="xref" href="ArcGIS.Desktop.Core.Portal.html">Portal</a>
- Assembly: ArcGIS.Desktop.Catalog.dll

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Parameters for an ArcGISPortal search query.</p>


## Object Signature

```csharp
public class PortalQueryParameters
```


## Members

### PortalQueryParameters(Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters" data-throw-if-not-resolved="false"></xref> class from a search bounding box.</p>


```csharp
public PortalQueryParameters(Envelope boundingBox)
```
### PortalQueryParameters(string)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters" data-throw-if-not-resolved="false"></xref> class from a query string.</p>


```csharp
public PortalQueryParameters(string query)
```
### PortalQueryParameters(string, Envelope)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters" data-throw-if-not-resolved="false"></xref> class from a query string and search extent.</p>


```csharp
public PortalQueryParameters(string query, Envelope boundingBox)
```
### PortalQueryParameters(string, int)

- Kind: constructor

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Initializes a new instance of the <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters" data-throw-if-not-resolved="false"></xref> class from a query string and a limit.</p>


```csharp
public PortalQueryParameters(string query, int limit)
```
### BoundingBox

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets or sets the search extent for a spatial search.
A valid search requires either a bounding box, or a <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters.Query" data-throw-if-not-resolved="false"></xref>, or both.</p>


```csharp
public Envelope BoundingBox { get; set; }
```
### CreateForItemsInGroup(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Returns query parameters that will find items with a specified group.</p>


```csharp
public static PortalQueryParameters CreateForItemsInGroup(string groupId)
```
### CreateForItemsOfType(PortalItemType, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Returns query parameters that will find items with a specified type.</p>


```csharp
public static PortalQueryParameters CreateForItemsOfType(PortalItemType type, string search = "")
```
### CreateForItemsOfTypeInGroup(PortalItemType, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Returns query parameters that will find items with a specified type in the specified group.</p>


```csharp
public static PortalQueryParameters CreateForItemsOfTypeInGroup(PortalItemType type, string groupId, string search = "")
```
### CreateForItemsOfTypeWithOwner(PortalItemType, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Returns query parameters that will find items with a specified type and owner.</p>


```csharp
public static PortalQueryParameters CreateForItemsOfTypeWithOwner(PortalItemType type, string owner, string search = "")
```
### CreateForItemsOfTypes(IEnumerable&lt;PortalItemType&gt;, string, string, string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Returns query parameters that will find items with the specified types, group and owner.</p>


```csharp
public static PortalQueryParameters CreateForItemsOfTypes(IEnumerable<PortalItemType> types, string owner = "", string groupId = "", string search = "")
```
### CreateForItemsWithId(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Returns query parameters that will find items with a specified item Id.</p>


```csharp
public static PortalQueryParameters CreateForItemsWithId(string itemId)
```
### CreateForItemsWithOwner(string)

- Kind: method

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Returns query parameters that will find items with a specified item owner.</p>


```csharp
public static PortalQueryParameters CreateForItemsWithOwner(string owner)
```
### Limit

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets or sets the maximum number of results to be included in the result set response.
The default value is 10 and the maximum allowed value is 100.
The start index, along with the limit parameter can be used to paginate the search results.
The actual number of returned results may be less than <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters.Limit" data-throw-if-not-resolved="false"></xref>. This happens when the number of results
remaining after <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters.StartIndex" data-throw-if-not-resolved="false"></xref> is less than <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters.Limit" data-throw-if-not-resolved="false"></xref>.</p>


```csharp
public int Limit { get; set; }
```
### OrganizationId

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets or sets the organization id to use in the query.</p>


```csharp
public string OrganizationId { get; set; }
```
### Query

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets or sets the query string to search against.</p>


```csharp
public string Query { get; set; }
```
### SearchQuery

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets a formatted query string based on the PortalQueryParameter properties</p>


```csharp
public string SearchQuery { get; }
```
### SortField

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets or sets the field to sort by. (e.g for groups the allowed field names are title, owner, and created).</p>


```csharp
public string SortField { get; set; }
```
### SortOrder

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets or sets a value indicating whether order returns in ascending or descending order. Default is ascending.</p>


```csharp
public PortalQuerySortOrder SortOrder { get; set; }
```
### StartIndex

- Kind: property

<p sourcefile="api/ArcGIS.Desktop.Core.Portal.PortalQueryParameters.yml" sourcestartlinenumber="1">Gets or sets the index of the first entry in the result set response.
The index number is 1-based.
The default value of  <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters.StartIndex" data-throw-if-not-resolved="false"></xref> is 1 (e.g.,. the first search result).
The start index, along with the <xref href="ArcGIS.Desktop.Core.Portal.PortalQueryParameters.Limit" data-throw-if-not-resolved="false"></xref> parameter can be used to paginate the search results.</p>


```csharp
public int StartIndex { get; set; }
```


