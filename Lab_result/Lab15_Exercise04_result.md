## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/142d2af2-227d-461a-a349-95f67ab7e1d6)

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/2199e7ab-2aa2-479c-8887-af0f725a0567)

## อธิบายสิ่งที่พบในการทดลอง
### โค้ดเกี่ยวกับ Passing delegate as parameter
### `MyDelegate del = imdel + smdel;` รวม imdel กับ smdel เข้าด้วยกันใน del ทำให้เมื่อเรียก del("Hello world"); จะเรียกทั้ง MethodA และ MethodB
### `del += amdel;` เพิ่ม Anonymous Method เข้าไปด้วย ทำให้ del เรียก 3 เมธอดพร้อมกัน
### vdel -= imdel;` ลบ imdel ออกจาก del ทำให้เมื่อเรียก del("Hello world"); จะเหลือแค่ MethodB และ Anonymous Method
