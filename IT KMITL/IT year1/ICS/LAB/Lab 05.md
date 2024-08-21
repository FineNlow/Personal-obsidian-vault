## **1.) 7-segment Display**
	![[Pasted image 20240809115353.png]]![[Pasted image 20240809115528.png]]
### 1.1)K-map C0-c6(7 segment display)
- <mark style="background: #D2B3FFA6;">C0</mark>

| CD\AB  | 00  | 01  | 11   | 10    |
| ------ | --- | --- | ---- | ----- |
| **00** | 1   | 0   | x*** | 1**** |
| **01** | 0   | 1   | x*** | 1**** |
| **11** | 1** | 1** | x*   | x*    |
| **10** | 1** | 1** | x*   | x*    |
<span style="color:rgb(0, 176, 240)">Boolean expression :</span>
<span style="color:rgb(86, 90, 215)">C + A + BD +!B!D</span>
- <mark style="background: #FF5582A6;">C1</mark>

| CD\AB  | 00  | 01  | 11  | 10  |
| ------ | --- | --- | --- | --- |
| **00** | 1   | 1   | x   | 1   |
| **01** | 1   | 0   | x   | 1   |
| **11** | 1   | 1   | x   | x   |
| **10** | 0   | 0   | x   | x   |
<span style="font-style:italic; color:rgb(0, 176, 240)">Boolean expression :</span>
<span style="color:rgb(86, 90, 215)">!B + !C!D + CD</span>
- <mark style="background: #FFB86CA6;">C2</mark>

| CD\AB | 00  | 01  | 11  | 10  |
| ----- | --- | --- | --- | --- |
| **00**    | 1   | 1   | x   | 1   |
| **01**    | 1   | 1   | x   | 1   |
| **11**    | 1   | 1   | x   | x   |
| **10**    | 0   | 1   | x   | x   |
<span style="color:rgb(0, 176, 240)">Boolean expression :</span>
<span style="color:rgb(86, 90, 215)">B + !C + D</span>
- <mark style="background: #BBFABBA6;">C3</mark>

| CD\AB | 00  | 01  | 11  | 10  |
| ----- | --- | --- | --- | --- |
| **00**    | 1   | 0   | x   | 1   |
| **01**    | 0   | 1   | x   | 0   |
| **11**    | 1   | 0   | x   | x   |
| **10**    | 1   | 1   | x   | x   |
<span style="color:rgb(0, 176, 240)">Boolean expression :</span>
<span style="color:rgb(86, 90, 215)">C!D + !BC + !B!D + B!CD</span>
- <mark style="background: #ABF7F7A6;">C4</mark>

| CD\AB | 00  | 01  | 11  | 10  |
| ----- | --- | --- | --- | --- |
| **00**    | 1   | 0   | x   | 1   |
| **01**    | 0   | 0   | x   | 0   |
| **11**    | 0   | 0   | x   | x   |
| **10**    | 1   | 1   | x   | x   |
<span style="color:rgb(0, 176, 240)">Boolean expression :</span>
<span style="color:rgb(86, 90, 215)">!B!D + C!D</span>
- <mark style="background: #ADCCFFA6;">C5</mark>

| CD\AB | 00  | 01  | 11  | 10  |
| ----- | --- | --- | --- | --- |
| **00**    | 1   | 1   | x   | 1   |
| **01**    | 0   | 1   | x   | 1   |
| **11**    | 0   | 0   | x   | x   |
| **10**    | 0   | 1   | x   | x   |
<span style="color:rgb(0, 176, 240)">Boolean expression :</span>
<span style="color:rgb(86, 90, 215)">A + !C!D + B!C + B!D
</span>
- <mark style="background: #CACFD9A6;">C6</mark>

| CD\AB  | 00  | 01  | 11  | 10  |
| ------ | --- | --- | --- | --- |
| **00** | 0   | 1   | x   | 1   |
| **01** | 0   | 1   | x   | 1   |
| **11** | 1   | 0   | x   | x   |
| **10** | 1   | 1   | x   | x   |
<span style="color:rgb(0, 176, 240)">Boolean expression :</span> 
<span style="color:rgb(86, 90, 215)">A + B!C + B!D + !BC</span> 
