## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/53b1d72b-13de-4d37-b4c0-bbde3a8f575e)

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/41c3c33b-7a2c-444c-93af-42b8b0fcaee7)

## อธิบายสิ่งที่พบในการทดลอง
### โค้ดนี้เป็นการใช้งาน Delegate กับเมธอดทั้งแบบ Instance และ Static 
### ในคลาส InstanceMethod มีเมธอดชื่อ MethodA ที่รับพารามิเตอร์เป็น string
### ในคลาส StaticMethod มีเมธอดชื่อ MethodB ที่รับพารามิเตอร์เป็น string
### `MyDelegate del = im.MethodA;` สร้าง instance ของ Delegate ชื่อ del และผูกไว้กับเมธอด MethodA ของ im
### `del = StaticMethod.MethodB;` เปลี่ยน Delegate del ไปอ้างอิงยังเมธอดแบบ static MethodB ของคลาส StaticMethod
