# TALLER-1
primera tarea
SEMAFORO
En este proyecto realice un semáforo, como se indica a la hora de hacer la conexiones y como se ve
en el circuito, se debe saber cuál es el lado positivo y negativo del led para que después no se vaya
presentar un corto o cause el daño del arduino, lo siguiente fue trabajar con 3 resistencias de 220
para que no dañe el led y sea conectad a tierra, para que se pueda ver mejor la iluminación del led.
Con el código creado en la aplicación de arduino para cumplir el funcionamiento querido, al elegir
cuanto tiempo que quiera que funcionara cada led para que se vea su utilidad. 
Código de arduino
void setup()
{
 pinMode(2, OUTPUT);
 pinMode(4, OUTPUT);
 pinMode(7, OUTPUT);
 void loop()
{
 digitalWrite(2, HIGH);delay(3000); // Wait for 3000 millisecond(s)
 digitalWrite(7, LOW);
 delay(250); // Wait for 250 millisecond(s)
 delay(3000); // Wait for 3000 millisecond(s)
 digitalWrite(2, LOW);
 delay(250); // Wait for 250 millisecond(s)
 digitalWrite(4, HIGH);
 delay(1500); // Wait for 1500 millisecond(s)
 digitalWrite(4, LOW);
 delay(100); // Wait for 100 millisecond(s)
 digitalWrite(7, HIGH);
 }
