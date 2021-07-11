int LED = 9;
int brightness = 121;
int delaytime = 500;
void setup ()
{
pinMode (LED,OUTPUT) ;
}
void loop ()
{
brightness = 255;
analogWrite (LED,brightness);
delay (delaytime);
brightness =127;
analogWrite (LED,brightness);
delay (delaytime);
brightness = 64;
analogWrite (LED,brightness);
delay (delaytime);
brightness = 0;
analogWrite (LED,brightness);
delay (delaytime);
}
