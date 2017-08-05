# pointInPolygon
In the domain of spatial prediction, it is useful to know the frequency of an event (usually represented by a point layer) over the environment (usually represented by a polygon layer), over time (usually present as fields in the point layer). To achieve that, the R environment requires, in general, the use of a function (like sp::over()) that returns a matrix of points in polygons. However, this leads to a loss of data associated to the event (points layer). 

Initally created to this function can overcome this issue, this function was developped in the context of the veterinay sciences. It thus accepts the flowing parameters :

1. P1 :
2: P2 :
3. P4 :
4. P5 :

## Example of use

point


The function returns a data frame, that can be summarized (see P1), or presented in short format (see P3) for convinience. The last alllows future merge operation to incorporate to the polygon layer.
