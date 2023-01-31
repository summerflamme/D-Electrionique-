//de 
     int led1=2;
     int led2=7;
     int led3=6;
     int led4=5;
     int delais=100;
     int bouton=4; 

void setup()
{
    pinMode(led1, OUTPUT);
    pinMode(led2, OUTPUT);
    pinMode(led3, OUTPUT);
    pinMode(led4, OUTPUT);
    digitalWrite(led1,HIGH);
    digitalWrite(led2,HIGH);
    digitalWrite(led3,HIGH);
    digitalWrite(led4,HIGH);
        do{
            delay(10);
             } while(analogRead(2) < 200);
                randomSeed(millis());
               
}
void loop()
{
  delais=delais/1.7; 
if (delais<300)
   
   {
 switch(random(1,6)){


    
  //affiche un 1
    digitalWrite(led1,LOW);
    digitalWrite(led2,LOW);
    digitalWrite(led3,LOW);
    digitalWrite(led4,HIGH);
        delay(delais); 
     


   // affiche un 2
      digitalWrite(led1,LOW);
      digitalWrite(led2,HIGH);
      digitalWrite(led3,LOW);
      digitalWrite(led4,LOW);
      delay(delais); 


   // affiche un 3
      digitalWrite(led1,LOW);
      digitalWrite(led2,HIGH);
      digitalWrite(led3,LOW);
      digitalWrite(led4,HIGH);
      delay(delais);


   // affiche un 4
      digitalWrite(led1,HIGH);
      digitalWrite(led2,HIGH);
      digitalWrite(led3,LOW);
      digitalWrite(led4,LOW);
     delay(delais); 


    // affiche un 5
       digitalWrite(led1,HIGH);
       digitalWrite(led2,HIGH);
       digitalWrite(led3,LOW);
       digitalWrite(led4,HIGH);
       delay(delais); 


    // affiche un 6
       digitalWrite(led1,HIGH);
       digitalWrite(led2,HIGH);
       digitalWrite(led3,HIGH);
       digitalWrite(led4,LOW);
       delay(delais); 

   }
  if(delais<8){
    switch(random(1,6)){


      case 1:
       digitalWrite(led1,LOW);
       digitalWrite(led2,LOW);
       digitalWrite(led3,LOW);
       digitalWrite(led4,HIGH);
    break;


        case 2:
         digitalWrite(led1,LOW);
         digitalWrite(led2,HIGH);
         digitalWrite(led3,LOW);
         digitalWrite(led4,LOW);
      break; 


        case 3:
          digitalWrite(led1,LOW);
          digitalWrite(led2,HIGH);
          digitalWrite(led3,LOW);
          digitalWrite(led4,HIGH);
        break;


        case 4:
          digitalWrite(led1,HIGH);
          digitalWrite(led2,HIGH);
          digitalWrite(led3,LOW);
          digitalWrite(led4,LOW);
        break; 


        case 5:
         digitalWrite(led1,HIGH);
         digitalWrite(led2,HIGH);
         digitalWrite(led3,LOW);
            digitalWrite(led4,HIGH);
        break; 


        case 6:
          digitalWrite(led1,HIGH);
          digitalWrite(led2,HIGH);
          digitalWrite(led3,HIGH);
          digitalWrite(led4,LOW);
        break; 
       
}
      do
      {
      delay(10);
      } while(analogRead(2) < 200);
    delais=100;
 }
   }
}
    
