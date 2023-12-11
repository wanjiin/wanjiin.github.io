function setup() {
  createCanvas(windowWidth, windowHeight - 20);
}

function draw() {
  noFill();
  let s = second();
  stroke(random(255), random(255), random(255));
  
  if (s % 2 === 0) {
    strokeWeight(1);
  }
  else {
    strokeWeight(2);
  }
  curve(random(width * 0.25, width * 0.75), random(height * 0.25, height * 0.75), mouseX + random(-5, 5), mouseY + random(-5, 5),mouseX + random(-5, 5), mouseY + random(-5, 5), random(width * 0.25, width * 0.75), random(height * 0.25, height * 0.75));
}

function mouseClicked() {
  noLoop();
}

