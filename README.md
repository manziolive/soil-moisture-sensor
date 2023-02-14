# soil-moisture-sensor
testing mosture content value



#define AOUT_PIN A0 

void setup() {
  Serial.begin(9600);
}

void loop() {
  int value = analogRead(AOUT_PIN); 

  Serial.print("Moisture: ");
  Serial.println(value);

  delay(500);

}
