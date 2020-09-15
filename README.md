設定輸出2 3 4 5</br>
功能:讓4個LED同時亮起後停頓0.1秒

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


part2
設定輸出腳2 3 4 5 </br>
功能:LED從右向左逐一亮起停頓1秒


```c++
int LED=5;
void setup() {
  // put your setup code here, to run once:
for(int i=1;i<6;i++)

  pinMode (i,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
   for(int i=5;i>0;i--)

   digitalWrite(i, HIGH);
   if(LED>=2)
    digitalWrite(LED,LOW);
   
   else
     LED=6;
   LED--;
   delay(1000);
}
```


