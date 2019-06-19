# GSM_Security
Description: This Arduino code will interface Arduino uno board with 
             sim900mini board, 
             connected at Arduino pin 1 (5VR of GSM) and Arduino pin 0 (5VT of GSM).
Pin Connection
Arduino GSM
0   -   5VT
1   -   5VR
12  -   Sensor
13  -   Alarm
rowPins[ROWS] = {5, 4, 3, 2}; //connect to the row pinouts of the keypad
colPins[COLS] = {9, 8, 7, 6}; //connect to the column pinouts of the keypad

LCD Connection
rs = A5, en = A4, d4 = A3, d5 = A2, d6 = A1, d7 = A0;

*/
