# rect2
线在色块上
void setup(){
  size(900,900);
  background(255);
  initiateData();
}
void initiateData(){
  for(int i=0;i<50;i++){
    noStroke();
    fill(random(255),random(128),255);
    int a=int(random(600));
    rect(random(700),random(700),a,a);
  }
  for(int j=0;j<8;j++){
    stroke(255,random(150,255),0);
    strokeWeight(random(10,40));
    int a=int(random(900));
    line(0,a,900,a);
    int b=int(random(900));
    line(b,0,b,900);
  }
}
