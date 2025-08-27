# IOT-LED
Aqui irei te mostrar um IOT simples de LED


**COMO O BREADBOARD DEVE FICAR:**

<img width="500" height="500" alt="1" src="https://github.com/user-attachments/assets/83e863df-187c-4a89-aac0-348231355a6e" />

<img width="500" height="500" alt="2" src="https://github.com/user-attachments/assets/03cb0616-cb81-41b9-8583-784089958125" />

<img width="500" height="500" alt="3" src="https://github.com/user-attachments/assets/2042668f-a663-4004-ba6a-e16a6122ea17" />

<img width="500" height="500" alt="4" src="https://github.com/user-attachments/assets/b8bf5a00-5eeb-48ea-ac59-1104c31a912d" />


**CÓDIGO ARDUINO IDE:**

void setup() {
  //define o pino que estou usando, e se ele é uma entrada ou saída
  pinMode(13, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
