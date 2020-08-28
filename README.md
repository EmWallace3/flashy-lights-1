# flashy-lights-1
    //Learning to program my LilyPad materials - main board 325 and lights
void setup() {
    // Before you use a sew tab (pin), you must set it to be either an input or output:

  pinMode(5, OUTPUT); // Set pin 5 to be an output

}

void loop() {
  digitalWrite(5, HIGH); // Give pin 5 a HIGH voltage level (on), which lights up the LED
  delay(1000);           // Pause for 1000 milliseconds (one second), the LED stays on
  digitalWrite(5, LOW);  // Give pin 5 a LOW voltage level (off), which turns off the LED
  delay(1000);           // Pause for 1000 milliseconds (one second), the LED stays off

}
