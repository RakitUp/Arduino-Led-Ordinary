# Arduino-Led-Ordinary
//  Running LED Ordinary 
//  LED located at pin 8,9,10  
void setup() 
{     
    pinMode(8,OUTPUT);
    pinMode(9,OUTPUT);
    pinMode(10,OUTPUT); 
}  
void loop() 
{      
    digitalWrite(8, HIGH);delay(500);
    digitalWrite(8, LOW);delay(500);
    
    digitalWrite(9, HIGH);delay(500);
    digitalWrite(9, LOW);delay(500);
    
    digitalWrite(10, HIGH);delay(500);
    digitalWrite(10, LOW);delay(500); 
}
