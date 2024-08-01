# Automatic-Irrigation-System-using-ESP8266-Module
// Define the pin where the LED is connected
const int ledPin = D4;

void setup() {
  // Initialize the digital pin as an output
  pinMode(ledPin, OUTPUT);
}

void loop() {
  // Turn the LED on
  digitalWrite(ledPin, HIGH);
  // Wait for 1000 milliseconds (1 second)
  delay(1000);
  // Turn the LED off
  digitalWrite(ledPin, LOW);
  // Wait for 1000 milliseconds (1 second)
  delay(1000);
}
