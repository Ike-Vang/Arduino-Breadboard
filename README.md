# Arduino-Breadboard
Things with Arduino and a breadboard


#define INPIN 7
#define OUTPIN 13

// constants won't change. They're used here to
// set pin numbers:
void setup() {
  pinMode(OUTPIN,OUTPUT);
  pinMode(INPIN, INPUT);
}

void loop() {
  bool button;
  button = digitalRead(INPIN);
  digitalWrite(OUTPIN, button);
}
