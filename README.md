#ใบงานที่ 5
##เรื่อง การใช้งานคำสั่ง Console.WriteLine()
##วัตถุประสงค์
1). เพื่อให้นักศึกษาบอกวิธีการใช้คำสั่งแสดงผลบน Text Mode ในภาษา C# ได้
2). เพื่อให้นักศึกษาสามารถปรับแต่งคำสั่งแสดงผลทางหน้าจอตามต้องการได้

##ขั้นเตรียมการทดลอง
1). สร้าง Project ตั้งชื่อเป็น Lab5 เพื่อทดลองการใช้งานคำสั่ง Console.WriteLine()
ลำดับขั้นการทดลอง
(หมายเหตุ ในรูปประกอบที่มี namespace เป็น Lab4 รบกวนแก้เป็น Lab5 ด้วยครับ)
2). ทดลองเรื่องจำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

 2.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic1.png)

  2.2). รันโปรแกรม และบันทึกผลที่ได้

โปรแกรมจะแสดงผลออกมาเป็น ซึ่งจะอยู่คนละบรรทัด

            This is text 1.
            This is text 2.
            This is text 3.
            
![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture.PNG?raw=true)



 2.3). แก้โปรแกรมตามรูปด้านล่างนี้
 
  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic2.png)

 2.4). รันโปรแกรม และบันทึกผลที่ได้

ผลการรันจะออกมาเป็น 3 and 6
![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture1.PNG?raw=true)



###คำถาม 5.1 เครื่องหมาย { }  ในคำสั่ง Console.WriteLine() มีลักษณะการใช้งานอย่างไร

การระบุตำแหน่งตัวเลขที่เราป้อน

###คำถาม 5.2  ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย

ใช้งานได้ไม่ได้เพราะตัวเลขมีแค่สองตำแหน่งแค่ 0 และ 1 แต่ถ้าเราเพิ่มตัวเลขให้หลายๆตำแหน่ง ก็สามารถใช้{0} {2} {3} ดังตัวอย่างข้างล่าง

![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture2.PNG?raw=true)
![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture3.PNG?raw=true)
 
 2.5). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic3.png)

 2.6). รันโปรแกรม และบันทึกผลที่ได้

ผลการรันเลขออกมาเป็น 6, 3 and 6
![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture3-1.PNG?raw=true)

3). ทดลองเรื่องการกำหนดความกว้างของอาร์กิวเมนต์

  3.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic4.png)

  3.2). รันโปรแกรม และบันทึกผลที่ได้

ผลการรันเลข 1 จะออกมาตามตำแหน่งที่เรากำหนด
![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture4.PNG?raw=true)


###คำถาม 5.3 การกำหนดความกว้างของอาร์กิวเมนต์ด้วยเครื่องหมาย { , }  ในคำสั่ง Console.WriteLine() มีรูปแบบการใช้งานอย่างไร

ตัวแรกคือตำแหน่งของตัวเลขที่เราป้อน ตัวที่สองคือตำแหน่งตัวอักษรบนหน้าจอแสดงผลว่าเท่ากับกี่ตัวอักษรเช่น {0,2} คือ 0 เลขตำแหน่งที่ 0 , 2 ตำแหน่งตัวอักษรในบรรทัดตำแหน่งที่ 2 คือ นำเลขตำแหน่งที่ 0 ไปแสดงผลในบรรทัดตำแหน่งตัวอักษรตัวที่2


4). ทดลองเรื่องการกำหนดรูปแบบของอาร์กิวเมนต์
  4.1). แก้โปรแกรมตามรูปด้านล่างนี้

  ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic5.png)

  4.2). รันโปรแกรม และบันทึกผลที่ได้

![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture5.PNG?raw=true)

5). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของอาร์กิวเมนต์
  5.1). แก้โปรแกรมตามรูปด้านล่างนี้
 
 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic6.png)

  5.2). รันโปรแกรม และบันทึกผลที่ได้
  
 ผลการรันคือจะจำกัดความกว้างของอาร์กิวเมนต์แค่ 20 ตัวอักษร
  ![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture6.PNG?raw=true)

6). ทดลองเรื่องการกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์
  6.1). แก้โปรแกรมตามรูปด้านล่างนี้

 ![](https://github.com/Desktop-Programming-Lab-2559/LAB-05/blob/master/img/pic7.png)

  6.2). รันโปรแกรม และบันทึกผลที่ได้
  
  การแสดงผลทศนิยมคือ 
  
                    F1 ทศนิยม 1 ตำแหน่ง
  
                    F2 ทศนิยม 2 ตำแหน่ง
                    
                    F3 ทศนิยม 3 ตำแหน่ง
                    
                    F4 ทศนิยม 4 ตำแหน่ง
                    
                    F5 ทศนิยม 5 ตำแหน่ง
                  
  ![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture7.PNG?raw=true)


## แบบฝึกหัด จงระบุ output ของบรรทัดคำสั่งต่อไปนี้

```csharp
1.  string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
2.    Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
3.    Console.WriteLine("Hello " + "World");
4.    Console.WriteLine("Here comes a slash \\");
5.    Console.WriteLine("|{0, 10}|", 999);
6.    Console.WriteLine("|{0,-10}|", 000);
7.    Console.WriteLine("The value: {0}.", 500);
8.    Console.WriteLine("The value: {0:C}.", 500);
9.    Console.WriteLine("{0,-10:F4}", 12.3456789);
10.   Console.WriteLine("{0,-10:C}", 12.3456789);
11.   Console.WriteLine("{0,-10:E3}", 12.3456789);
12.   Console.WriteLine("{0,-10:x}", 65535);
13.   Console.WriteLine("{0,-10:X}", 65535);
14.   int i; 
      Console.WriteLine("Value\tSquared\tCubed"); 
      for(i = 1; i < 10; i++) 
          Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i); 
15.    Console.WriteLine("{0:#.###}.", 1234.56789);
```

![](https://github.com/Jarukan57030147/LAB-05/blob/master/img/Capture8.PNG?raw=true)
