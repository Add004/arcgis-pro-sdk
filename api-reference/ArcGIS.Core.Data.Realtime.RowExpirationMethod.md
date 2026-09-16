# RowExpirationMethod

- Type: enum
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Core.html">Core</a>.<a class="xref" href="ArcGIS.Core.Data.html">Data</a>.<a class="xref" href="ArcGIS.Core.Data.Realtime.html">Realtime</a>
- Assembly: ArcGIS.Core.dll

<p sourcefile="api/ArcGIS.Core.Data.Realtime.RowExpirationMethod.yml" sourcestartlinenumber="1">Specifies the row expiration method.</p>


## Object Signature

```csharp
public enum RowExpirationMethod
```


## Members

### MaxAge

- Kind: field

<p>Rows will be automatically deleted when their age in the table becomes older than the limit.</p>
<p>If the <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable" data-throw-if-not-resolved="false"></xref> has a TrackID field (see <xref href="ArcGIS.Core.Data.Realtime.RealtimeTableDefinition.HasTrackIDField" data-throw-if-not-resolved="false"></xref>), then this expiration method is applied per track
    without limiting the number of tracks that can exist in the table.
    </p>


```csharp
MaxAge = 1
```
### MaxCount

- Kind: field

<p>Whenever the maximum row count is reached, the oldest rows will be deleted in the order they arrived until the number of rows in the table is less than or equal than the maximum count.</p>
<p>If the <xref href="ArcGIS.Core.Data.Realtime.RealtimeTable" data-throw-if-not-resolved="false"></xref> has a TrackID field (see <xref href="ArcGIS.Core.Data.Realtime.RealtimeTableDefinition.HasTrackIDField" data-throw-if-not-resolved="false"></xref>), then this expiration method is applied per track
    without limiting the number of tracks that can exist in the table.
    </p>


```csharp
MaxCount = 0
```


