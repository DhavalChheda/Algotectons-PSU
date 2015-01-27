# Algotectons-PSU
Assignment 1


int x = 1;
float y = 200;
float z;

void setup() {
  size(600, 200);
  smooth();
  noStroke();
  
}

void draw() {
  background(#333333);
  ellipse(x, y, 40, 40);
  
  x=x+1;
  y=y*0.99;
  
 
}
