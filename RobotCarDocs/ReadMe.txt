ESP32 based robot car:

1. ESP32 -iig shuud auto program hiideg bolgono. Gehdee io0 GND tai jumper hiih connector gargana. 
2. Sensor connector (Ultra sonic, Servo motor PWMs,... )
3. TP4056 deer load sharing protection nemne. (P channel mosfet)
4. Battery holder Through hole.
5. Sogtuu dugui tohiruulna. 

{
 


https://www.aliexpress.com/item/1005005906429335.html?spm=a2g0o.productlist.main.5.6296554diHHrpj&algo_pvid=e2c2c4b3-b5d9-4b03-a885-f8ae8016df3c 



https://www.aliexpress.com/item/1005006151935085.html?spm=a2g0o.productlist.main.1.6296554diHHrpj&algo_pvid=e2c2c4b3-b5d9-4b03-a885-f8ae8016df3c



}


6. GND, GND1 net-uudiig dahin sain harah.

7. RGB, Photoresistor, DHT11, Servo, Ultrasonic sensor(Trig and echo pins not neccesarry pwm), buttons and leds, potentiometer(ADC1 use), Touch ( Gpio32 is working good for touch)

8. pull-downs on motor driver





ESP32's Free Gpios to use :

oks:

MOTOR DRIVER: 13 23 25 26 27 4 33
LEFT GIOs : 5 16 17 18 19 21 22

( SPIs: 23, 19, 18, 5 )
( I2C: 21, 22 )
( UART2: 16, 17 )
( ADC2 & DAC1,2: 25, 26 )
( Touch: 32 )

LED outputs: 23 25 26 4 33
Button inputs: 17 18 19 21 22

