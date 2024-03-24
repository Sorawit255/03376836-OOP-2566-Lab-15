## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/f8606ad1-f4a5-41fe-9bd7-98b737645e06)

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/9c58bbd3-db65-48fe-a252-19cae8356d1b)

## อธิบายสิ่งที่พบในการทดลอง
### โค้ดดังกล่าวเป็นการใช้งาน Action Delegate 
```
Action<int, int> sum = (a, b) =>
{
    var x = a + b;
    System.Console.WriteLine("result = " + x);
};
sum(8, 2);
```
### ทำการสร้าง Action sum ที่รับพารามิเตอร์ทั้งหมด 2 ตัวและกำหนดให้ชี้ไปยัง Lambda Expression ซึ่งมีการคำนวณผลรวมของตัวแปร a และ b  และแสดงผล
