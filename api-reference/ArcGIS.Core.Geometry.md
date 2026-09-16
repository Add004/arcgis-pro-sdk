# ArcGIS.Core.Geometry

- Type: namespace
- Assembly: ArcGIS.Core.dll




## Members

### AngularUnit

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.AngularUnit.yml" sourcestartlinenumber="1">Represents an angular unit of measure used by a <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, or in measurement conversion functions.</p>


### ArcOrientation

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.ArcOrientation.yml" sourcestartlinenumber="1">Describes the orientation of an <xref href="ArcGIS.Core.Geometry.EllipticArcSegment" data-throw-if-not-resolved="false"></xref>. The orientation is defined as the direction between the 'from' and 'to' points of the arc.</p>


### AreaUnit

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.AreaUnit.yml" sourcestartlinenumber="1">Represents an area unit of measure.</p>


### AsRatioOrLength

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.AsRatioOrLength.yml" sourcestartlinenumber="1">Describes how the distance along the curve is interpreted. See the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SetMsAsDistance(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.AsRatioOrLength)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryNormal(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cSystem.Double%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>, <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPoint(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cSystem.Double%2cArcGIS.Core.Geometry.AsRatioOrLength)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GetSubCurve(ArcGIS.Core.Geometry.Multipart%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.AsRatioOrLength)" data-throw-if-not-resolved="false"></xref> functions as examples.</p>


### AttributeFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.AttributeFlags.yml" sourcestartlinenumber="1">Flags used when creating a geometry in some GeometryBuilderEx methods specifying which attributes, Z, M, and ID, the
newly created geometry should have.
Use bitwise OR to specify more than one attribute. For example, to specify
that the geometry should have Z and M-values, specify AttributeFlags.HasZ | AttributeFlags.HasM.</p>


### BasicMaterial

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.BasicMaterial.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.Material" data-throw-if-not-resolved="false"></xref> class describing basic graphic properties.</p>


### ClothoidCreateMethod

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.ClothoidCreateMethod.yml" sourcestartlinenumber="1">The method of creation for a clothoid.
Used with <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx.CreatePolyline(ArcGIS.Core.Geometry.MapPoint%2cSystem.Double%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.ArcOrientation%2cArcGIS.Core.Geometry.ClothoidCreateMethod%2cSystem.Double%2cArcGIS.Core.Geometry.CurveDensifyMethod%2cSystem.Double%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref>.</p>


### CompositeGeographicTransformation

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeGeographicTransformation.yml" sourcestartlinenumber="1">A composite geographic transformation class is an ordered list of <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref> classes.
The geographic transformations are applied in the order they are stored.</p>


### CompositeHVDatumTransformation

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.CompositeHVDatumTransformation.yml" sourcestartlinenumber="1">A composite hv (horizontal/vertical) datum transformation class is an ordered list of <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> classes.
The hv datum transformations are applied in the order they are stored.</p>


### Coordinate2D

- Kind: struct

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate2D.yml" sourcestartlinenumber="1">A lightweight structure that holds X and Y values.</p>


### Coordinate3D

- Kind: struct

<p sourcefile="api/ArcGIS.Core.Geometry.Coordinate3D.yml" sourcestartlinenumber="1">A structure containing methods to manipulate 3D vertices and 3D vectors.</p>


### CoordinateSystemFilter

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemFilter.yml" sourcestartlinenumber="1">Coordinate System Filter. Use a filter as input to <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetPredefinedCoordinateSystemList(ArcGIS.Core.Geometry.CoordinateSystemFilter)" data-throw-if-not-resolved="false"></xref>.
Can be used as a bit mask to get multiple coordinate system types in one list.</p>


### CoordinateSystemListEntry

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.CoordinateSystemListEntry.yml" sourcestartlinenumber="1">Provides the well-known ID (WKID), name and category (or region) of a particular coordinate system.</p>


### CubicBezierBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.CubicBezierSegment" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### CubicBezierSegment

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.CubicBezierSegment.yml" sourcestartlinenumber="1">Represents a third degree cubic Bezier curve for use in a <xref href="ArcGIS.Core.Geometry.Multipart?text=Multipart" data-throw-if-not-resolved="false"></xref> geometry.  To create a cubic bezier segment use
the <xref href="ArcGIS.Core.Geometry.CubicBezierBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


### CurveDensifyMethod

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.CurveDensifyMethod.yml" sourcestartlinenumber="1">Methods to specify curve densification.<br>
Used with <xref href="ArcGIS.Core.Geometry.PolylineBuilderEx.CreatePolyline(ArcGIS.Core.Geometry.MapPoint%2cSystem.Double%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.ArcOrientation%2cArcGIS.Core.Geometry.ClothoidCreateMethod%2cSystem.Double%2cArcGIS.Core.Geometry.CurveDensifyMethod%2cSystem.Double%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ConstructGeodeticLineFromPoints(ArcGIS.Core.Geometry.GeodeticCurveType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.CurveDensifyMethod%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>,
and <xref href="ArcGIS.Core.Geometry.GeometryEngine.ConstructGeodeticLineFromDistance(ArcGIS.Core.Geometry.GeodeticCurveType%2cArcGIS.Core.Geometry.MapPoint%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.CurveDensifyMethod%2cSystem.Double)" data-throw-if-not-resolved="false"></xref></p>


### Datum

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Datum.yml" sourcestartlinenumber="1">Describes the horizontal datum of a geographic coordinate system or the vertical datum of a vertical coordinate system.
It is returned from <xref href="ArcGIS.Core.Geometry.SpatialReference.Datum" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.VerticalCoordinateSystem.Datum" data-throw-if-not-resolved="false"></xref>.</p>


### DatumTransformation

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.DatumTransformation.yml" sourcestartlinenumber="1">An abstract class for datum transformations. Currently, a datum transformation can be a <xref href="ArcGIS.Core.Geometry.GeographicTransformation" data-throw-if-not-resolved="false"></xref>,
a <xref href="ArcGIS.Core.Geometry.CompositeGeographicTransformation" data-throw-if-not-resolved="false"></xref>, a <xref href="ArcGIS.Core.Geometry.HVDatumTransformation" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.CompositeHVDatumTransformation" data-throw-if-not-resolved="false"></xref>.</p>


### EllipticArcBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcBuilderEx.yml" sourcestartlinenumber="1">A builder for creating an <xref href="ArcGIS.Core.Geometry.EllipticArcSegment" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### EllipticArcSegment

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.EllipticArcSegment.yml" sourcestartlinenumber="1">Represents an elliptic arc segment for use in a <xref href="ArcGIS.Core.Geometry.Multipart?text=Multipart" data-throw-if-not-resolved="false"></xref> geometry.  To create an elliptic arc segment use
the <xref href="ArcGIS.Core.Geometry.EllipticArcBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


### Envelope

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Envelope.yml" sourcestartlinenumber="1">An envelope is an axis-aligned box described by the coordinates
of the lower left corner and the coordinates of the upper right corner. To create an envelope use the
<xref href="ArcGIS.Core.Geometry.EnvelopeBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


### EnvelopeBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.EnvelopeBuilderEx.yml" sourcestartlinenumber="1">A builder for creating an <xref href="ArcGIS.Core.Geometry.Envelope" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### EsriShapeExportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToEsriShape(ArcGIS.Core.Geometry.EsriShapeExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToEsriShape(ArcGIS.Core.Geometry.EsriShapeExportFlags%2cArcGIS.Core.Geometry.Geometry%2cSystem.Byte%5b%5d%40)" data-throw-if-not-resolved="false"></xref> methods.</p>


### EsriShapeImportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.EsriShapeImportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ImportFromEsriShape(ArcGIS.Core.Geometry.EsriShapeImportFlags%2cSystem.Byte%5b%5d%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>


### ExtendFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.ExtendFlags.yml" sourcestartlinenumber="1">Extend flag options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.Extend(ArcGIS.Core.Geometry.Polyline%2cArcGIS.Core.Geometry.Polyline%2cArcGIS.Core.Geometry.ExtendFlags)" data-throw-if-not-resolved="false"></xref> function.</p>


### ExtrapolateMMethod

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.ExtrapolateMMethod.yml" sourcestartlinenumber="1">The method to use when extrapolating M-values.
See <xref href="ArcGIS.Core.Geometry.GeometryEngine.ExtrapolateMs(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.ExtrapolateMMethod%2cSystem.Int32%2cSystem.Int32%2cSystem.Int32%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref></p>


### FromGeoCoordinateMode

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.FromGeoCoordinateMode.yml" sourcestartlinenumber="1">Determines the format of the coordinate description.  See <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx.FromGeoCoordinateString(System.String%2cArcGIS.Core.Geometry.SpatialReference%2cArcGIS.Core.Geometry.GeoCoordinateType%2cArcGIS.Core.Geometry.FromGeoCoordinateMode)" data-throw-if-not-resolved="false"></xref>.</p>


### GeoConTransformationBuilder

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeoConTransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a GeoCon grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


### GeoCoordinateType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.GeoCoordinateType.yml" sourcestartlinenumber="1">Options for representing different coordinate string notations. Used with the <xref href="ArcGIS.Core.Geometry.ToGeoCoordinateParameter" data-throw-if-not-resolved="false"></xref> class as part of
the <xref href="ArcGIS.Core.Geometry.MapPoint.ToGeoCoordinateString(ArcGIS.Core.Geometry.ToGeoCoordinateParameter)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx.FromGeoCoordinateString(System.String%2cArcGIS.Core.Geometry.SpatialReference%2cArcGIS.Core.Geometry.GeoCoordinateType%2cArcGIS.Core.Geometry.FromGeoCoordinateMode)" data-throw-if-not-resolved="false"></xref> functions.</p>


### GeodesicEllipseParameter

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicEllipseParameter.yml" sourcestartlinenumber="1">Options for creating a geodesic ellipse with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodesicEllipse(ArcGIS.Core.Geometry.GeodesicEllipseParameter%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> function.</p>


### GeodesicSectorParameter

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeodesicSectorParameter.yml" sourcestartlinenumber="1">Options for creating a geodesic sector with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodesicSector(ArcGIS.Core.Geometry.GeodesicSectorParameter%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> function.</p>


### GeodeticCurveType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.GeodeticCurveType.yml" sourcestartlinenumber="1">Curve type options for use with the geodetic functions. See <xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodeticDensifyByLength(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.GeodeticCurveType)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodeticDensifyByDeviation(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cArcGIS.Core.Geometry.GeodeticCurveType)" data-throw-if-not-resolved="false"></xref> or
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GeodeticMove(System.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.MapPoint%7d%2cArcGIS.Core.Geometry.SpatialReference%2cSystem.Double%2cArcGIS.Core.Geometry.LinearUnit%2cSystem.Double%2cArcGIS.Core.Geometry.GeodeticCurveType)" data-throw-if-not-resolved="false"></xref>.</p>


### GeographicTransformation

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformation.yml" sourcestartlinenumber="1">A geographic transformation is used when
projecting geometries between two different geographic coordinate systems. A geographic
transformation converts everything that needs to be changed including the units,
prime meridian, and the ellipsoid. Every transformation is defined in a particular forward
direction, say from GCS A to GCS B, but all are reversible. For example, a geographic
transformation may be defined to convert from NAD27 to WGS84. If you are projecting from
WGS84 to NAD27, you can use the reversed form of the transformation.</p>


### GeographicTransformationListEntry

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeographicTransformationListEntry.yml" sourcestartlinenumber="1">Provides the name, well-known ID (WKID), and WKIDs of the spatial references from which and to which the data will be projected.</p>


### Geometry

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Geometry.yml" sourcestartlinenumber="1">An abstract base class for objects that define geometric shapes. Geometry objects can be used
as geometry definitions for rendering data.</p>


### GeometryBag

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBag.yml" sourcestartlinenumber="1">A class representing a GeometryBag.   To create a geometry bag use the <xref href="ArcGIS.Core.Geometry.GeometryBagBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


### GeometryBagBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBagBuilderEx.yml" sourcestartlinenumber="1">Builder for creating a <xref href="ArcGIS.Core.Geometry.GeometryBag?text=GeometryBag" data-throw-if-not-resolved="false"></xref>.</p>


### GeometryBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryBuilderEx.yml" sourcestartlinenumber="1">An abstract base class for geometry builders.</p>


### GeometryDimensionType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryDimensionType.yml" sourcestartlinenumber="1">Describes the dimensionality of the geometry object. Use with <xref href="ArcGIS.Core.Geometry.GeometryEngine.Intersection(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.GeometryDimensionType)" data-throw-if-not-resolved="false"></xref> .</p>


### GeometryEngine

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryEngine.yml" sourcestartlinenumber="1">Utility for performing geometric operations.</p>


### GeometryType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.GeometryType.yml" sourcestartlinenumber="1">Describes the different types of geometry.</p>


### GridUnit

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.GridUnit.yml" sourcestartlinenumber="1">Represents a grid unit for a geographic location.</p>


### HVDatumTransformation

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.HVDatumTransformation.yml" sourcestartlinenumber="1">A hv (horizontal/vertical) datum transformation is used when
projecting Z-Aware geometries between two different geographic coordinate systems and two
different vertical coordinate systems. As with geographic transformations, a hv datum
transformation converts everything that needs to be changed including the units,
prime meridian, and the ellipsoid. In addition, a hv datum transformation transforms height.
Every transformation is defined in a particular forward direction, but all are reversible.
For example, suppose your Z-Aware geometry is in WGS84 with vertical coordinate system EGM2008_Geoid,
and you want to project to NAD83_2011 with vertical coordinate system NAD83_2011.
A hv datum transformation is defined to project your Z-Aware geometry from WGS84 with
vertical coordinate system EGM2008_Geoid to NAD83_2011 with vertical coordinate system NAD83_2011.
If you are projecting from NAD83_2011 with vertical coordinate system NAD83_2011 to
WGS84 with vertical coordinate system EGM2008_Geoid to NAD83_2011, you can use the reversed
form of the transformation.</p>


### HarnTransformationBuilder

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.HarnTransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a Harn grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


### IGeometryEngine

- Kind: interface

<p sourcefile="api/ArcGIS.Core.Geometry.IGeometryEngine.yml" sourcestartlinenumber="1">Geometry Engine interface. Performs geometric operations.</p>


### JPEGTexture

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.JPEGTexture.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.TextureMap" data-throw-if-not-resolved="false"></xref> that contains a Jpeg image. Wrap a JPEGTexture within a <xref href="ArcGIS.Core.Geometry.TextureResource" data-throw-if-not-resolved="false"></xref> for use with a <xref href="ArcGIS.Core.Geometry.BasicMaterial" data-throw-if-not-resolved="false"></xref>
when defining a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>


### JsonExportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.JsonExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToJson(ArcGIS.Core.Geometry.JsonExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> method.</p>


### JsonImportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.JsonImportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ImportFromJson(ArcGIS.Core.Geometry.JsonImportFlags%2cSystem.String)" data-throw-if-not-resolved="false"></xref> method.</p>


### LeftOrRightSide

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.LeftOrRightSide.yml" sourcestartlinenumber="1">When used in <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPointAndDistance(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double%40%2cSystem.Double%40%2cArcGIS.Core.Geometry.LeftOrRightSide%40)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPointAndDistance(ArcGIS.Core.Geometry.Segment%2cArcGIS.Core.Geometry.SegmentExtensionType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double%40%2cSystem.Double%40%2cArcGIS.Core.Geometry.LeftOrRightSide%40)" data-throw-if-not-resolved="false"></xref>,
describes whether the input point is on the left or right side of the curve.
When used in <xref href="ArcGIS.Core.Geometry.GeometryEngine.SideBuffer(ArcGIS.Core.Geometry.Polyline%2cSystem.Double%2cArcGIS.Core.Geometry.LeftOrRightSide%2cArcGIS.Core.Geometry.LineCapType)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.GeometryEngine.SideBuffer(System.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.Polyline%7d%2cSystem.Double%2cArcGIS.Core.Geometry.LeftOrRightSide%2cArcGIS.Core.Geometry.LineCapType)" data-throw-if-not-resolved="false"></xref>,
describes which side of the input geometry to construct the buffer.
The direction of the curve determines the left and right sides.</p>


### LineBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.LineBuilderEx.yml" sourcestartlinenumber="1">Builder for creating a <xref href="ArcGIS.Core.Geometry.LineSegment?text=LineSegment" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### LineCapType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.LineCapType.yml" sourcestartlinenumber="1">Defines the shape of the line ending for polylines and points (square or round).
See <xref href="ArcGIS.Core.Geometry.GeometryEngine.GraphicBuffer(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.LineJoinType%2cArcGIS.Core.Geometry.LineCapType%2cSystem.Double%2cSystem.Double%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.GraphicBuffer(System.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.Geometry%7d%2cSystem.Double%2cArcGIS.Core.Geometry.LineJoinType%2cArcGIS.Core.Geometry.LineCapType%2cSystem.Double%2cSystem.Double%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref>,
<xref href="ArcGIS.Core.Geometry.GeometryEngine.SideBuffer(ArcGIS.Core.Geometry.Polyline%2cSystem.Double%2cArcGIS.Core.Geometry.LeftOrRightSide%2cArcGIS.Core.Geometry.LineCapType)" data-throw-if-not-resolved="false"></xref>,
and <xref href="ArcGIS.Core.Geometry.GeometryEngine.SideBuffer(System.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.Polyline%7d%2cSystem.Double%2cArcGIS.Core.Geometry.LeftOrRightSide%2cArcGIS.Core.Geometry.LineCapType)" data-throw-if-not-resolved="false"></xref></p>


### LineJoinType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.LineJoinType.yml" sourcestartlinenumber="1">Defines the connection of the buffer at corners. See <xref href="ArcGIS.Core.Geometry.GeometryEngine.GraphicBuffer(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.LineJoinType%2cArcGIS.Core.Geometry.LineCapType%2cSystem.Double%2cSystem.Double%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Core.Geometry.GeometryEngine.GraphicBuffer(System.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.Geometry%7d%2cSystem.Double%2cArcGIS.Core.Geometry.LineJoinType%2cArcGIS.Core.Geometry.LineCapType%2cSystem.Double%2cSystem.Double%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref>.</p>


### LineSegment

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.LineSegment.yml" sourcestartlinenumber="1">A class representing a straight line between a start and end point for use in a <xref href="ArcGIS.Core.Geometry.Multipart?text=Multipart" data-throw-if-not-resolved="false"></xref> geometry. To create a line segment use
the <xref href="ArcGIS.Core.Geometry.LineBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


### LinearUnit

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.LinearUnit.yml" sourcestartlinenumber="1">Represents a linear unit of measure used by a <xref href="ArcGIS.Core.Geometry.Geometry" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>, or in measurement conversion functions.</p>


### MSubCurveRelation

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.MSubCurveRelation.yml" sourcestartlinenumber="1">Information about where an M-value falls relative to a multipart. Use with <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetSubCurveBetweenMsEx(ArcGIS.Core.Geometry.Multipart%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.MSubCurveRelation%40%2cArcGIS.Core.Geometry.MSubCurveRelation%40)" data-throw-if-not-resolved="false"></xref> method.</p>


### MapPoint

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.MapPoint.yml" sourcestartlinenumber="1">A MapPoint represents a single location in space. The location consists of X and Y values and optionally a Z and/or M value.
To create a MapPoint use the <xref href="ArcGIS.Core.Geometry.MapPointBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


### MapPointBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.MapPointBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.MapPoint" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### Material

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Material.yml" sourcestartlinenumber="1">An abstract Material instance.</p>


### MinorOrMajor

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.MinorOrMajor.yml" sourcestartlinenumber="1">Indicates whether the arc is a minor or major arc. An arc is minor if the central angle
is less than PI radians (180 degrees) and major otherwise.  Used with <xref href="ArcGIS.Core.Geometry.EllipticArcBuilderEx.CreateCircularArc(ArcGIS.Core.Geometry.MapPoint%2cSystem.Double%2cSystem.Double%2cSystem.Double%2cArcGIS.Core.Geometry.ArcOrientation%2cArcGIS.Core.Geometry.MinorOrMajor%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref>.</p>


### MonotonicType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.MonotonicType.yml" sourcestartlinenumber="1">Describes if values on a geometry are all ascending, all descending, or neither.  See the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetMMonotonic(ArcGIS.Core.Geometry.Multipart)" data-throw-if-not-resolved="false"></xref> method.</p>


### Monotonicity

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.Monotonicity.yml" sourcestartlinenumber="1">Describes trends in the value of an attribute.
See the <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetMMonotonicity(ArcGIS.Core.Geometry.Multipart)" data-throw-if-not-resolved="false"></xref> method.</p>


### Multipart

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Multipart.yml" sourcestartlinenumber="1">An abstract base class for multipart geometry types.</p>


### MultipartBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.MultipartBuilderEx.yml" sourcestartlinenumber="1">An abstract base class for creating a <xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> or a <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref>.</p>


### Multipatch

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Multipatch.yml" sourcestartlinenumber="1">A class representing a multipatch.</p>


### MultipatchBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### MultipatchConstructType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.MultipatchConstructType.yml" sourcestartlinenumber="1">Describes the set of predetermined multipatch forms that can be constructed.</p>


### Multipoint

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Multipoint.yml" sourcestartlinenumber="1">A Multipoint is a ordered collection of <xref href="ArcGIS.Core.Geometry.MapPoint?text=map+points" data-throw-if-not-resolved="false"></xref>. To create a multipoint use the
<xref href="ArcGIS.Core.Geometry.MultipointBuilderEx" data-throw-if-not-resolved="false"></xref> object.</p>


### MultipointBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.MultipointBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Multipoint" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### NTv2TransformationBuilder

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.NTv2TransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a NTv2 grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


### NTv2VelocityTransformationBuilder

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.NTv2VelocityTransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a NTv2 grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


### NadCon5TransformationBuilder

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.NadCon5TransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a NadCon5 grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


### NadConTransformationBuilder

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.NadConTransformationBuilder.yml" sourcestartlinenumber="1">A builder for creating a NadCon grid transformation.
A grid transformation is a type of geographic transformation that uses a grid dataset to perform the transformation.</p>


### NonSimpleReason

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="1">Specifies the reason that a non-simple geometry is non-simple. Returned from <xref href="ArcGIS.Core.Geometry.GeometryEngine.GetNonSimpleReason(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.NonSimpleReason%40%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref>.
See <a href="https://github.com/esri/arcgis-pro-sdk/wiki/ProConcepts-Geometry#simplifyasfeature-and-issimpleasfeature">SimplifyAsFeature and IsSimpleAsFeature Wiki page</a>.
Note: This enumeration coincides with ArcObjects esriNonSimpleReasonEnum
<a href="https://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm#esriNonSimpleReasonEnum.htm" sourcefile="api/ArcGIS.Core.Geometry.NonSimpleReason.yml" sourcestartlinenumber="4">https://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm#esriNonSimpleReasonEnum.htm</a></p>


### OffsetType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.OffsetType.yml" sourcestartlinenumber="1">Offset options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.Offset(ArcGIS.Core.Geometry.Geometry%2cSystem.Double%2cArcGIS.Core.Geometry.OffsetType%2cSystem.Double)" data-throw-if-not-resolved="false"></xref> method.</p>


### Patch

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Patch.yml" sourcestartlinenumber="1">A class to create a patch for a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>. Use <xref href="ArcGIS.Core.Geometry.MultipatchBuilderEx" data-throw-if-not-resolved="false"></xref> to construct a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref> from
patches.</p>


### PatchType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.PatchType.yml" sourcestartlinenumber="1">Describes the type of the patch.</p>


### Polygon

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Polygon.yml" sourcestartlinenumber="1">A class representing a polygon.</p>


### PolygonBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.PolygonBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Polygon?text=polygon" data-throw-if-not-resolved="false"></xref> whose methods can be called on any thread.</p>


### Polyline

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Polyline.yml" sourcestartlinenumber="1">A class representing a polyline.</p>


### PolylineBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.PolylineBuilderEx.yml" sourcestartlinenumber="1">A builder for creating a <xref href="ArcGIS.Core.Geometry.Polyline?text=polyline" data-throw-if-not-resolved="false"></xref>.</p>


### PositiveDirection

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.PositiveDirection.yml" sourcestartlinenumber="1">The positive direction for a vertical coordinate system of a <xref href="ArcGIS.Core.Geometry.SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


### ProjectionTransformation

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.ProjectionTransformation.yml" sourcestartlinenumber="1">A projection transformation describes parameters used to project geometries from one spatial reference to another. Used in the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ProjectEx(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.ProjectionTransformation)" data-throw-if-not-resolved="false"></xref> method.</p>


### ProximityResult

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.ProximityResult.yml" sourcestartlinenumber="1">Result from a GeometryEngine proximity operation such as <xref href="ArcGIS.Core.Geometry.GeometryEngine.NearestPoint(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.MapPoint)" data-throw-if-not-resolved="false"></xref> or <xref href="ArcGIS.Core.Geometry.GeometryEngine.NearestVertex(ArcGIS.Core.Geometry.Geometry%2cArcGIS.Core.Geometry.MapPoint)" data-throw-if-not-resolved="false"></xref>.</p>


### ReadOnlyPartCollection

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPartCollection.yml" sourcestartlinenumber="1">A Read-only collection of <xref href="ArcGIS.Core.Geometry.ReadOnlySegmentCollection" data-throw-if-not-resolved="false"></xref> parts used by
<xref href="ArcGIS.Core.Geometry.Polyline" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.Polygon" data-throw-if-not-resolved="false"></xref>.</p>


### ReadOnlyPointCollection

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlyPointCollection.yml" sourcestartlinenumber="1">A read-only collection of <xref href="ArcGIS.Core.Geometry.MapPoint?text=MapPoints" data-throw-if-not-resolved="false"></xref>.</p>


### ReadOnlySegmentCollection

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.ReadOnlySegmentCollection.yml" sourcestartlinenumber="1">A read only collection of <xref href="ArcGIS.Core.Geometry.Segment" data-throw-if-not-resolved="false"></xref> classes.</p>


### Segment

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Segment.yml" sourcestartlinenumber="1">Abstract class representing a start and end point and how they are connected. The most common is a straight line <xref href="ArcGIS.Core.Geometry.LineSegment" data-throw-if-not-resolved="false"></xref>.</p>


### SegmentBuilderEx

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentBuilderEx.yml" sourcestartlinenumber="1">Abstract base class for builders of all segment types to include:</p>
<ul><li>Line</li><li>Bezier curve</li><li>Elliptic Arc</li></ul><remarks>The SegmentBuilderEx methods can be called on any thread.</remarks>


### SegmentExtensionType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentExtensionType.yml" sourcestartlinenumber="1">Describes if, how and where to extend segments. See the <xref href="ArcGIS.Core.Geometry.GeometryEngine.QueryPointAndDistance(ArcGIS.Core.Geometry.Multipart%2cArcGIS.Core.Geometry.SegmentExtensionType%2cArcGIS.Core.Geometry.MapPoint%2cArcGIS.Core.Geometry.AsRatioOrLength%2cSystem.Double%40%2cSystem.Double%40%2cArcGIS.Core.Geometry.LeftOrRightSide%40)" data-throw-if-not-resolved="false"></xref> function.</p>


### SegmentType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.SegmentType.yml" sourcestartlinenumber="1">Describes the type of line segment. See the <xref href="ArcGIS.Core.Geometry.Segment.SegmentType" data-throw-if-not-resolved="false"></xref> property.</p>


### SimplifyType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.SimplifyType.yml" sourcestartlinenumber="1">Options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SimplifyPolyline(ArcGIS.Core.Geometry.Polyline%2cArcGIS.Core.Geometry.SimplifyType%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref> functions.</p>


### SliceType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.SliceType.yml" sourcestartlinenumber="1">Options for use with the <xref href="ArcGIS.Core.Geometry.GeometryEngine.SlicePolygonIntoEqualParts(ArcGIS.Core.Geometry.Polygon%2cSystem.Int32%2cSystem.Double%2cArcGIS.Core.Geometry.SliceType)" data-throw-if-not-resolved="false"></xref> method.</p>


### SpatialReference

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReference.yml" sourcestartlinenumber="1">Class representing a spatial reference.</p>


### SpatialReferenceBuilder

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferenceBuilder.yml" sourcestartlinenumber="1">Builder for creating a <xref href="ArcGIS.Core.Geometry.SpatialReference?text=SpatialReference" data-throw-if-not-resolved="false"></xref>.</p>


### SpatialReferences

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.SpatialReferences.yml" sourcestartlinenumber="1">Contains some common spatial references.</p>


### Texture

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Texture.yml" sourcestartlinenumber="1">An abstract texture class.</p>


### TextureCompressionType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.TextureCompressionType.yml" sourcestartlinenumber="1">Describes the compression type of the material texture.</p>


### TextureMap

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.TextureMap.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.Texture" data-throw-if-not-resolved="false"></xref> class that contains a raster image.</p>


### TextureResource

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.TextureResource.yml" sourcestartlinenumber="1">A texture resource class that wraps a <xref href="ArcGIS.Core.Geometry.TextureResource.Texture" data-throw-if-not-resolved="false"></xref> instance.</p>


### ToGeoCoordinateMode

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateMode.yml" sourcestartlinenumber="1">Determines how to handle the geographic coordinate system of the spatial reference.  Certain older geographic coordinate systems will cause one of the letters
of the string to be shifted.  This process makes it easier to identify coordinates that are based on a non-WGS84 datum.</p>


### ToGeoCoordinateParameter

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.ToGeoCoordinateParameter.yml" sourcestartlinenumber="1">A class used as the parameter to <xref href="ArcGIS.Core.Geometry.MapPoint.ToGeoCoordinateString(ArcGIS.Core.Geometry.ToGeoCoordinateParameter)" data-throw-if-not-resolved="false"></xref>.</p>


### UncompressedTexture

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.UncompressedTexture.yml" sourcestartlinenumber="1">A <xref href="ArcGIS.Core.Geometry.TextureMap" data-throw-if-not-resolved="false"></xref> that contains a raw uncompressed raster image.  Wrap an UncompressedTexture within a <xref href="ArcGIS.Core.Geometry.TextureResource" data-throw-if-not-resolved="false"></xref> for use with
a <xref href="ArcGIS.Core.Geometry.BasicMaterial" data-throw-if-not-resolved="false"></xref> when defining a <xref href="ArcGIS.Core.Geometry.Multipatch" data-throw-if-not-resolved="false"></xref>.</p>


### Unit

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.Unit.yml" sourcestartlinenumber="1">A common base class between all units; linear, area, angular, grid.</p>


### UnitType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.UnitType.yml" sourcestartlinenumber="1">Describes the different types of units.</p>


### UnitTypeCode

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.UnitTypeCode.yml" sourcestartlinenumber="1">Available unit codes</p>


### UpdateMMethod

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.UpdateMMethod.yml" sourcestartlinenumber="1">The method to use when calibrating M-values.
See <xref href="ArcGIS.Core.Geometry.GeometryEngine.CalibrateByMs(ArcGIS.Core.Geometry.Multipart%2cSystem.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.MapPoint%7d%2cArcGIS.Core.Geometry.UpdateMMethod%2cSystem.Double)" data-throw-if-not-resolved="false"></xref>
and <xref href="ArcGIS.Core.Geometry.GeometryEngine.CalibrateMsByDistance(ArcGIS.Core.Geometry.Multipart%2cSystem.Collections.Generic.IEnumerable%7bArcGIS.Core.Geometry.MapPoint%7d%2cArcGIS.Core.Geometry.UpdateMMethod%2cSystem.Boolean%2cSystem.Double)" data-throw-if-not-resolved="false"></xref></p>


### VcsType

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.VcsType.yml" sourcestartlinenumber="1">Specifies the supported vertical coordinate system types.</p>


### VerticalCoordinateSystem

- Kind: class

<p sourcefile="api/ArcGIS.Core.Geometry.VerticalCoordinateSystem.yml" sourcestartlinenumber="1">Represents a vertical coordinate system and provides access to its definition and properties.
A vertical coordinate system defines the origin used for height or depth values.</p>


### WkbExportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.WkbExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToWKB(ArcGIS.Core.Geometry.WkbExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> and
<xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToWKB(ArcGIS.Core.Geometry.WkbExportFlags%2cArcGIS.Core.Geometry.Geometry%2cSystem.Byte%5b%5d%40)" data-throw-if-not-resolved="false"></xref> methods.</p>


### WkbImportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.WkbImportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ImportFromWKB(ArcGIS.Core.Geometry.WkbImportFlags%2cSystem.Byte%5b%5d%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>


### WktExportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.WktExportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ExportToWKT(ArcGIS.Core.Geometry.WktExportFlags%2cArcGIS.Core.Geometry.Geometry)" data-throw-if-not-resolved="false"></xref> method.</p>


### WktFormatMode

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.WktFormatMode.yml" sourcestartlinenumber="1">The format mode for <xref href="ArcGIS.Core.Geometry.SpatialReference.GetWkt2(ArcGIS.Core.Geometry.WktFormatMode)" data-throw-if-not-resolved="false"></xref> and <xref href="ArcGIS.Core.Geometry.SpatialReferenceBuilder.GetWkt2(ArcGIS.Core.Geometry.WktFormatMode)" data-throw-if-not-resolved="false"></xref>.</p>


### WktImportFlags

- Kind: enum

<p sourcefile="api/ArcGIS.Core.Geometry.WktImportFlags.yml" sourcestartlinenumber="1">Specifies the flags that control the behavior of the <xref href="ArcGIS.Core.Geometry.GeometryEngine.ImportFromWKT(ArcGIS.Core.Geometry.WktImportFlags%2cSystem.String%2cArcGIS.Core.Geometry.SpatialReference)" data-throw-if-not-resolved="false"></xref> method.</p>




