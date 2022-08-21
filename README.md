int x;
int y;
int speed;

void setup() {
  size(600,600);
  x = 100;
  y = 500;
  speed = 5;
} 

void draw(){
  background(#3A7E86);
  ellipse(x,300,75,75);
  x = x + speed;
  if( x > 500) {
    speed = -speed;
  }
  if( x < 100) {
    speed = -speed;
  }
}  
