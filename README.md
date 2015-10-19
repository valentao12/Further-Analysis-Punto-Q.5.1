# Further-Analysis-Punto-Q.5.1
Punto Q.5.1 
X=linspace(0,2*pi,20); % creates a 20 element vector X from 0 to

>> Y1= sin(X); % creates a 20 element vector Y1 = sin(X) 

>> Y2 =cos(X); % creates a 20 element vector of Y2 = 

>> Y3 =Y1+Y2;

>> Y4 =Y1-Y2;

>> plot (X,Y1,’K*:’) % plots sin(X) vs X with a dotted (:) black 

>> % indicating the points with a star (*) 

>> hold on

>> plot(X,Y2,’r--’) % plots cos(X) vs X with a dashed (--) red 

>> hold on

>> plot(X,Y3,’b’) % plots [sin(X) + cos(X)] vs X with a solid 

>> hold on

>> plot(X,Y4,’g’) % plots [sin(X) - cos(X)] vs X with a solid 

>> hold off

>> box off % suppresses the figure box

2pi

for 0 < X < 2pi

cos(X) for 0 < X < 2pi

(k) line

marker

(r) line

line (blue)

green (g) line
