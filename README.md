# tarea1
%ejemplo1%
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(0);
  stroke(220)
  line(0,0,200,200);
  line(400,0,200,200);
  line(200,200,200,400);
  
}
%ejemplo2%
function setup() {
  createCanvas(600, 600);
}

function draw() {
  background(218,33,40);
 fill(36,231,17);
  rect(200,0,400,600);
  fill(0,88,155);
  rect(400,0,200,600);
  
}
%ejemplo3%
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(255);
  fill(218,33,40)
  ellipse(200,200,290,290)
  fill(255);
  ellipse(200,200,270,270)
  strokeWeight(30)
  line(100,100,300,300)
  stroke(218,33,40)
}
