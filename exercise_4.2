

//--------------- PADDLE CLASS -----------------//


class Paddle {
  float x, y;
  float vx, vy;
  float radius;
  color c;
  int size;

  Paddle(float x) {
    size = 20;
    noStroke();
    colorMode(HSB, 100);
    this.x = x;
    y = random(height-radius);
    vx = (random(4));
    vy = 4;
    c = color(random(100), 100, 100);
  }

  void draw() {
    fill(c);
    rect(x, y, size, size*2);
  }

  void move() {
    y = y + vy;
    if (x < size || x > width-size) {
      vx = -vx;
    }
    if (y <= 0 || y > height-size*2) {
      vy = -vy;
    }
  }
}



//--------------- BALL CLASS -----------------//



class Ball {
  float x, y;
  float vx, vy;
  float radius;
  color c;

  Ball() {
    noStroke();
    colorMode(HSB, 100);
    x = random(width-radius);
    y = random(height-radius);
    radius = 10;
    vx = (random(4));
    vy = (random(4));
    c = color(random(100), 100, 100);
  }

  void draw() {
    fill(c);
    ellipse(x, y, radius*2, radius*2);
  }

  void move() {
    x = x + vx;
    y = y + vy;
    if (x < radius || x > width-radius) {
      vx = -vx;
    }
    if (y < radius || y > height-radius) {
      vy = -vy;
    }
  }
}

Ball b;
Paddle p1, p2; 

void setup() {
  size(500, 500);

  b = new Ball();
  p1 = new Paddle(20);
  p2 = new Paddle(460);
}

void draw() {
  colorMode(RGB, 100);
  background(255, 255, 255);

  //Draw Paddle 1
  p1.draw();
  p1.move();

  //Draw Paddle 2
  p2.draw();
  p2.move();


  // Draw 1st ball
  b.draw();
  b.move();


  // Reposition first ball at mouse cursor
  if (mousePressed) {
    b.x = mouseX;
    b.y = mouseY;
  }
}
