## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/c12c74c6-8b1b-4468-b7af-f5821a3f8be0)

## บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
![image](https://github.com/Sorawit255/03376836-OOP-2566-Lab-15/assets/144196505/ff48e808-4935-4bcd-a4c9-4ebae92597e3)

## อธิบายสิ่งที่พบในการทดลอง
### `public delegate void MyDelegate(string message);` ประกาศ Delegate ชื่อ MyDelegate ซึ่งค่าเป็น string
```
// 2. add target method to delegate
MyDelegate myDel1 = new MyDelegate(MyMethod);
MyDelegate myDel2 = MyMethod;
```
### เป็นการสร้างอ็อบเจกต์ของ MyDelegate และกำหนดให้ชี้ไปที่ MyMethod ได้โดยตรง หรือใช้ชื่อเมธอดโดยไม่ต้องใส่ new MyDelegate()
```
// 3. Invoke delegate
myDel1("Hello World");        // เรียกใช้ MyMethod ผ่าน myDel1
myDel1.Invoke("Hello Mars");  // เรียกใช้ MyMethod ผ่าน myDel1
myDel2("Hello Saturn");       // เรียกใช้ MyMethod ผ่าน myDel2
```
