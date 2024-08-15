# js-nsilvwfunction setup() {
  createCanvas(1000, 1000);
  background("pink");
}

function draw() {

  stroke("yellow");

  fill("black");

  //console.log(mouseIsPressed); {

  if (mouseIsPressed) {
    rect(mouseX,mouseY,20,35);
    
  }
}
