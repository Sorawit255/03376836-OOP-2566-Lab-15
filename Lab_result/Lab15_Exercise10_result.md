## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/688185c6-e9c5-4590-ac0a-0cd970cba5d3)

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/17509a15-a174-4233-acf3-bb0b16c0f185)

## อธิบายสิ่งที่พบในการทดลอง
### `Func<int, int, int> add = Add;` สร้าง delegate Func(สำหรับเมธอดที่มีการส่งค่าคืนกลับ)
### `int c = add(a,b);` เรียกใช้ตัวแปร Func โดยส่งพารามิเตอร์ตามที่กำหนดไว้ใน delegate และรับค่าที่ส่งคืนกลับมา
### `Func<string, string> convertToUpper = s => s.ToUpper();` ใช้ Lambda Expression เพื่อระบุเมธอดในรูปแบบที่ไม่ต้องประกาศเมธอดแยกไว้ โดยใช้รูปแบบ (พารามิเตอร์) => { คำสั่ง; }
