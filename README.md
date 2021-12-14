# java2d-quad


For more complex shapes, drawn from equation we follow:


Point p0 = new Point (300, 50); //Given point 
g2. drawstring ("p0", 50, 105);
Point p1= new Point (400, 180);//Given point 
g2. filloval (400, 180, 5, 5); 
//g2.drawstring ("control point",. 400, 180); 
Point p2 = new Point (110, 250);
//Given point 
g2. drawstring ("p2", 110, 255) ; 

double t = 0; 

int xl1= (int) (Math.pow(1 - t, 2) * p0.x + 2*t* (1 - t) * p1.x + t*t *p2.x) ; 

int y1= (int) (Math.pow(1 - t, 2) * p0.y + 2* t* (1 - t) * p1.y + t*t* p2. y); 

for (int i 0; i < 1000; i++) {
t = 0+ (i / 1000.0) * (1 - 0): 

int x2 = (int) (Math.pow(1 -t, 2) * p0.x + 2*t *(1 - t) * p1.x +t*t*p2.x);


int y2 = (int) (Math.pow(1-t, 2)*p0.y +2*t*(1-t)*p1.y + t*t*p2.y); 

g2.drawLine (x1, yl1, x2, y2); 
x1= x2;
y1 = y2; 


