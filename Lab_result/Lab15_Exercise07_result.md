## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/be59a536-0347-405d-b817-62423db22a0b)

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/325a7ff9-530b-49da-8c75-bd443f9b3eb2)

## อธิบายสิ่งที่พบในการทดลอง
### `delegate int Square(int num);` กำหนด Delegate ชื่อ Square
### `Square getSquare = x => x * x;` กำหนด Lambda Expression เพื่อสร้างเมธอดเป็น Square โดยใช้คีย์เวิร์ด =>
```
int num = 9;
int sqr = getSquare(num);
System.Console.WriteLine($"Square value of {num} is {sqr}");
```
### ใช้ตัวแปร getSquare ในการเรียกใช้งาน โดยส่งค่าที่ต้องการคำนวณกำลังสองเข้าไป
