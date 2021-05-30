# SI_lab2_193026

Control Flow Graph
![191230187_562886481361606_8805420433739061990_n (1)](https://user-images.githubusercontent.com/82288889/120120084-714e9880-c19b-11eb-8b52-77df28adeccc.jpg)\

Цикломатска комплексност -->

Цикломатската комплексност на графот е 8, што се добива од бројот на јазли кои носат одлука (7) + 1.

Тест случаи според критериумот Multiple condition -- >


I)	if (hr < 0 || hr > 24)
 1)
combination: TX
possible test case: -2, 2
branch: 

2)
combination: FT
possible test case: 5, 55
branch: 

3)
combination: FF
possible test case: 5, 2
branch: 


 II)	if (min < 0 || min > 59)
 1)
combination: TX
possible test case: -2, 2
branch: 

2)
combination: FT
possible test case: 5, 66
branch: 

3)
combination: FF
possible test case: 5, 2
branch: 


III)	if (sec >= 0 && sec <= 59)
 1)
combination: TF
possible test case: 2, 66
branch: 

2)
combination: TT
possible test case: 5, 22
branch: 

3)
combination: FX
possible test case: -3, 2
branch: 


III)	else if (hr == 24 && min == 0 && sec == 0)  
 1)
combination: TTT
possible test case: 24, 0, 0
branch: 

2)
combination: TTF
possible test case: 24, 0, 3
branch: 

3)
combination: FXX
possible test case: 3, 2, 0
branch: 

4)
combination: TFX
possible test case: 24, 2, 5
branch: 

....

Тест случаи според критериумот Every path
....

Објаснување на напишаните unit tests
... ...
3. 
4. 
