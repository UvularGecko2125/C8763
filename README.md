設定輸出2 3 4 5</br>
用途:讓4個LED同時亮起後停頓0.1秒

```c++
void setup() {

  // put your setup code here, to run once:

  for(int i=2;i<6;i++)

  pinMode (i,OUTPUT);

}



void loop() {

  // put your main code here, to run repeatedly:

  for(int i=2;i<6;i++)

   digitalWrite(i, LOW);

delay(100);

  for(int i=2;i<=6;i++)

   digitalWrite(i, HIGH);

delay(100);

}
```
![image](https://github.com/UvularGecko2125/C8763/blob/master/DSC_0005.JPG)
