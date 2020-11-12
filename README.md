# Research-Project-One
A theory based exploration of polygon-circle properties.<br/>
End result an approximation for polygon-circle accuracy.<br/>
End result also applicable as a dampened converging harmonic function.<br/>

Basis used include well-proven geometric properties:<br/>
Conservation of angle of a triangle,<br/>
Fundamental properties of arclength and radius,<br/>
Geometric properties of a right triangle,<br/>
Geometric properties of an isosceles triangle,<br/>
Pythagorean theorum,<br/>
Fundamental trigometric functions sine and cosine,<br/>
Sine-squared power reduction formula.<br/>


We start with a circle. The circle has a Radius(R) = 1<br/>
Within the circle is a triangle. The triangle has two sides (R).<br/>
Both (R) come from the circle center as Radii.<br/>
The angle between the Radii is not fixed, a variable.<br/>
There is a (M + V) third Radii halfway between the two.<br/>
There is a (E) chord between the original two Radii.<br/>
The (E) chord and the (M + V)third Radii intersect in the form of a cross.<br/>
The chord divides the third Radii into two segments, (V) the chord to circle edge, and (M) the circle center to chord.<br/>
What we have now is a polygon of sides R, angle (theta) and in terms of line segment (V)<br/>

R = 1<br/>
R = M + V<br/>
(Theta) = 2 PI / (N)<br/>
(N) is number of polygons.<br/>
We have isosceles triangle R, R, E<br/>
We have the conservation equations of:<br/>
PI/N + (PI - (2PI/N))/(2) + PI/2 = PI (TOTAL ANGLE OF A TRIANGLE) and <br/>
2PI/N + PI - 2PI/N + PI = 2PI (CONSERVATION OF ANGLE)<br/>

We have isosceles triangle lone angle (iota) and double angle (theta)<br/>
(iota)/2 + (theta) = PI/2 (CONSERVATION OF ANGLE)<br/>
PI/N + (theta) = PI/2 (CONSERVATION OF ANGLE)<br/>

We have isosceles triangle divided down the midsection so that angle (iota) is halved<br/>
We have a^2 + b^2 = c^2 where<br/>
(E/2)^2 + (M)^2 = (R)^2 = 1<br/>
Which simplifies to:<br/>
E = (2)(sqrt(1-(M^2)))<br/>

We have arclength for S = R(theta)<br/>
R = 1 ::: S = (theta)<br/>
for N divisions so<br/>
divisions(N) = 2PI/(N) = S = (theta)<br/>

V = 1 - M<br/>
sin(PI/N) = E/2R<br/>

E = 2Rsin(PI/N)
M = sqrt((4-(2)(sin(PI/N)^2)))/2<br/>
Which after a great deal of algebra simplifies to <br/>
V = ( (2 + sqrt(2)) / (2) ) ( sqrt(1-cos(2PI/N)) )<br/>
and so we have V(N)<br/>
So now if you tell me how many polygons you want to use to approximate a circle,<br/>
I can tell you how good that approximation is with a converging dampened harmonic equation with true computational costs being a cosine and a squareroot.<br/>
The equation even works with decimals because the domain of (N) is all real numbers(with minor exceptions).<br/>
The actual results of V can be normalized to 1, or whatever, and using some inversion converted to a scale of 0 to 1 where 1 is best fit.<br/>
Or 0 to 10. Or however the scale would be wanted, it really doesnt matter as long as it starts at 0 and goes to some max.<br/>

