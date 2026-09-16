# PrinterSettings

- Type: class
- Namespace: <a class="xref" href="ArcGIS.html">ArcGIS</a>.<a class="xref" href="ArcGIS.Desktop.html">Desktop</a>.<a class="xref" href="ArcGIS.Desktop.Mapping.html">Mapping</a>
- Assembly: ArcGIS.Desktop.Mapping.dll

<p sourcefile="api/ArcGIS.Desktop.Mapping.PrinterSettings.yml" sourcestartlinenumber="1">Provides a base set of properties that all export formats inherit.</p>


## Object Signature

```csharp
[Obsolete("Deprecated at 3.5. Please use PrinterSettingsInfo instead")]
public class PrinterSettings
```

## Remarks

<p>  When exporting a <xref href="ArcGIS.Desktop.Mapping.MapView?text=MapView" data-throw-if-not-resolved="false"></xref>, the size of the output image is based on the <b>Resolution</b> and the <b>Height</b> and <b>Width</b> properties. 
    For example, if the output resolution is 96 and height and width are both 960 then the output image size will be 960 pixels by 960 pixels and 10 inches by 10 inches. 
    The geographic area for an exported <b>MapView</b> is generated based on its <xref href="ArcGIS.Desktop.Mapping.Camera" data-throw-if-not-resolved="false"></xref> location which represents the center of the view.
    </p>
<p>
    When exporting a <xref href="ArcGIS.Desktop.Layouts.Layout?text=Layout" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Desktop.Layouts.MapFrame?text=MapFrame" data-throw-if-not-resolved="false"></xref>, the height and width are obtained from the size of the object
    in page units and the <b>Height</b> and <b>Width</b> properties are ignored.  For example, if a <b>MapFrame</b> is 5 inches by 5 inches and the resolution is 300, the output image
    will be 1500 pixels by 1500 pixels and remain 5 inches by 5 inches.
    </p>





