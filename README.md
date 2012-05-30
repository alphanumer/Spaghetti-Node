Spaghetti-Node
==============

algorithm for transforming spaghetti code DXF entities into topology based ArcNode format.
this is part of homework assignment and will later be part of an open source GIS project i will undertake.

the code is in C#, and holds a the following namespaces and classes:

Namespace GeoClasses: holds classes for Point, Line, Polyline and Polygon,
                      as well as static class PolylineToPolygon that will convert closed polylines
                      into polygons. this namespace basically holds all geo data as received from DXF file.
Namespace ArcNode: holds classes for Node, Arc, Parcel, as well as a static class SpaghettiToArcNode
                   that will transform all of the topology relevant data into arc node format.