# EasyGIS
GIS functions using KNIME:

1) What is the geodesic distance between two features?

- Between a point and the closest edge of a polygon
- Between a point and another point
- Between the closest edge of a polygon to the closest edge of another polygon

2) What is the network distance between two features?

- Between a point and the closest edge of a polygon
- Between a point and another point
- Between the closest edge of a polygon to the closest edge of another polygon

3) Is a point inside or outside a polygon?

- Is the point completely within the polygon (not including features on the boundary) -- “completely contain within”
- Is the point within the polygon (including features on the boundary) -- “contain within”
- Is the point only touching the boundary (so neither in or out) -- Clementini

Project contains:

KNIME Workflow containing the KNIME Node called EasyGIS.

EasyGIS Node implements the GIS functions in Python.
