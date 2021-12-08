# Traffic-Lights
Traffic Light Simulation With Arduino

Code:

    //My Traffic Light Simulation With Arduino
    
    void setup()
    {
      pinMode(9, OUTPUT);
      pinMode(10, OUTPUT);
      pinMode(11, OUTPUT);
    }

    void loop()
    {
      digitalWrite(11, LOW);
      digitalWrite(9, HIGH);
      delay(2000); // Wait for 2000 millisecond(s)
      digitalWrite(9, LOW);
      digitalWrite(10, HIGH);
      delay(2000); // Wait for 2000 millisecond(s)
      digitalWrite(10, LOW);
      digitalWrite(11, HIGH);
      delay(2000); // Wait for 2000 millisecond(s)
      digitalWrite(11, LOW);
    }
    
Hope it helps :)
