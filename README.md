function setup() {
  createCanvas(windowWidth, windowHeight);
}

function draw() {
  rectMode(CENTER) 
  background(0);
  noFill()
  stroke(mouseX/7,mouseY/4,255)
  ellipse(25,25,50)
  rect(25,25,50)
  ellipse(50,50,20)
  
for(var j=0; j<windowHeight/50;j++){
  for(var i=0;i <windowWidth/50;i++) {
    ellipse(25+(i*50),25+(j*50),mouseX /10)
    ellipse(25+(i*50),25+(j*50),mouseY /10)
    ellipse(25+(i*50),25+(j*50),50)
    ellipse(25+(i*50),25+(j*50),40,30)
    ellipse(25+(i*50),25+(j*50),30,40)
    ellipse(25+(i*50),25+(j*50),30,20)
    ellipse(25+(i*50),25+(j*50),20,30)
    rect(25+(i*50),25+(j*50),50)
    ellipse(50+(i*50),50+(j*50),20)
    } 
  }

}
