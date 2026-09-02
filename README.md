# Speed-Control-Of-Dc-Motor-Using-Pwm
Speed Control Of Dc Motor Using Pwm
### PROGRAM
```
const int motorPin = 9;
const int potPin = A0;

void setup() {
pinMode (motorPin, OUTPUT) ;

}

void loop() {
int potValue = analogRead (potPin) ;
int pwmValue = map (potValue, 0, 1023, 0, 255);
analogWrite (motorPin, pwmValue);
}
```
### OUTPUT
<img width="1038" height="556" alt="image" src="https://github.com/user-attachments/assets/d2c0de3e-0217-434c-ba0a-f19759a6fe65" />
<img width="1021" height="552" alt="image" src="https://github.com/user-attachments/assets/ebbee99b-a49d-4041-8ee7-ab75a7eec8f2" />

### RESULT
Thus, the Speed Control Of Dc Motor Using Pwm is verified

