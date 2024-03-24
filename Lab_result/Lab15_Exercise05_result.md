## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/f40330d0-3d8e-40fc-af01-7c4c11177b66)

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/12d9fb64-5396-4c08-9e71-668baa9e6074)

## อธิบายสิ่งที่พบในการทดลอง
### `public delegate T Add<T>(T param1, T param2);` เป็นการประกาศ Generic Delegate ที่มีชื่อว่า Add
### `Add<int> sum = NumericSum;`/`Add<string> con = StringConcat;` สร้าง instance ของ Delegate ชื่อ sum/con โดยกำหนดให้ T เป็น int/string
### เมื่อเรียกใช้งาน จะแสดงผลจากการเรียกใช้งานเมธอด NumericSum และ StringConcat ตามลำดับ
