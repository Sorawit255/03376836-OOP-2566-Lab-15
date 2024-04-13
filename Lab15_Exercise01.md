# Lab 15 Exercise 1

## Delegate

1.สร้าง console application project

```cmd
dotnet new console --name Lab15_Ex01
```

2.เปลี่ยน code ให้เป็นดังต่อไปนี้

```cs
// 2. add target method to delegate
MyDelegate myDel1 = new MyDelegate(MyMethod);
MyDelegate myDel2 = MyMethod;

// 3. Invoke delegate
myDel1("Hello World");
myDel1.Invoke("Hello Mars");
myDel2("Hello Saturn");

static  void  MyMethod(string message)
{
    System.Console.WriteLine(message);
}

// 1. declare delegate
public delegate void MyDelegate(string message);
```

3.Build project โดยการใช้คำสั่ง

```cmd
dotnet build  Lab15_Ex01
```

ถ้ามีที่ผิดพลาดในโปรแกรม ให้แก้ไขให้ถูกต้อง

4.บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3

5.Run project โดยการใช้คำสั่ง

```cmd
dotnet run --project Lab15_Ex01
```

6.บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5

7.อธิบายสิ่งที่พบในการทดลอง
dd