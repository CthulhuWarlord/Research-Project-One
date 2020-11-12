# Research-Project-One
A theory based exploration of polygon-circle properties.
End result an approximation for polygon-circle accuracy.
End result also applicable as a dampened converging harmonic function.

Basis used include well-proven geometric properties:
Conservation of angle of a triangle,
Fundamental properties of arclength and radius,
Geometric properties of a right triangle,
Geometric properties of an isosceles triangle,
Pythagorean theorum,
Fundamental trigometric functions sine and cosine,
Sine-squared power reduction formula.


We start with a circle. The circle has a Radius(R) = 1
Within the circle is a triangle. The triangle has two sides (R).
Both (R) come from the circle center as Radii.
The angle between the Radii is not fixed, a variable.
There is a (M + V) third Radii halfway between the two.
There is a (E) chord between the original two Radii.
The (E) chord and the (M + V)third Radii intersect in the form of a cross.
The chord divides the third Radii into two segments, (V) the chord to circle edege, and (M) the circle center to chord.
What we have now is a polygon of sides R, angle (theta) and in terms of line segment (V)

R = 1
R = M + V
(Theta) = 2 PI / (N)
(N) is number of polygons.
We have isosceles triangle R, R, E
We have the conservation equations of:
PI/N + (PI - (2PI/N))/(2) + PI/2 = PI (TOTAL ANGLE OF A TRIANGLE) and 
2PI/N + PI - 2PI/N + PI = 2PI (CONSERVATION OF ANGLE)

We have isosceles triangle lone angle (iota) and double angle (theta)
(iota)/2 + (theta) = PI/2 (CONSERVATION OF ANGLE)
PI/N + (theta) = PI/2 (CONSERVATION OF ANGLE)

We have isosceles triangle divided down the midsection so that angle (iota) is halved
We have a^2 + b^2 = c^2 where
(E/2)^2 + (M)^2 = (R)^2 = 1
Which simplifies to:
E = (2)(sqrt(1-(M^2)))

We have arclength for S = R(theta)
R = 1 ::: S = (theta)
for N divisions so
divisions(N) = 2PI/(N) = S = (theta)

V = 1 - M
sin(PI/N) = E/2R

E = 2Rsin(PI/N)
M = sqrt((4-(2)(sin(PI/N)^2)))/2
Which after a great deal of algebra simplifies to 
V = ((2 + sqrt(2)) / (2)) (sqrt(1-cos(2PI/N))
and so we have V(N)
So now if you tell me how many polygons you want to use to approximate a circle,
I can tell you how good that approximation is with a converging dampened harmonic equation.
The equation even works with decimals because the domain of (N) is all real numbers(with minor exceptions).
The actual results of V can be normalized to 1, or whatever, and using some inversion converted to a scale of 0 to 1 where 1 is best fit.
Or 0 to 10. Or however the scale would be wanted, it really doesnt matter as long as it starts at 0 and goes to some max.

