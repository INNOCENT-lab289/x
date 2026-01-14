// Turn ON a light using Arduino

int lightPin = 13;   // Pin connected to the light

void setup() {
  pinMode(lightPin, OUTPUT);   // Set pin as output
}

void loop() {
  digitalWrite(lightPin, HIGH);  // Turn ON the light
}
