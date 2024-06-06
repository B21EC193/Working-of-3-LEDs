# Working-of-3-LEDs
const int a = 10;
const int b = 5;
const int c = 2;
void setup(){

  pinMode(10,OUTPUT);
  pinMode(5,OUTPUT);
  pinMode(2,OUTPUT);
}
void loop(){
digitalWrite(a,HIGH);
delay(1000);
digitalWrite(a,LOW);
delay(1000);
digitalWrite(5,HIGH);
delay(1000);
digitalWrite(5,LOW);
delay(1000);
digitalWrite(2,HIGH);
delay(1000);
digitalWrite(2,LOW);
delay(1000);
}
