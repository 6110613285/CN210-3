# Summary Report for CN210 : Computer Architecture
> หน้าเพจนี้จัดทำขึ้นเพื่อรวมรวมและสรุปเนื้อหาจากวิชา CN210 Computer Architecture ประจำปีการศึกษาที่ 2/2562

## HomeWork#1
**Jump Format (J-Format)**
* **คลิปวีดีโอของการบ้านครั้งที่1**
> [Click Here for HomeWork#1 video](https://youtu.be/37fsqcEbHfk)

* **คำอธิบายเกี่ยวกับการบ้านครั้งที่1**

**Jump Format** มี 2 ส่วน

|Op Code (6 bits)| Address (26 bits)|
|----------------|------------------|

ได้แก่
1. **Op Code (Operation Code)** : มีความยาว *6 bits* และ สำหรับ J-Format จะใช้ Op Code คือ `000010`
2. **Address (Jump Target Address)** : มีความยาว *26 bits* 
   * Note : ที่จริงแล้วใน สถาปัตยกรรมแบบ MIPs รหัสคำสั่งจะมีความยาว *32 bits* แต่จะต้องนำมาทำเป็น *26 bits* เพื่อใช้เป็น Address


**วิธีการแปลง *32 bits* เป็น *26 bits***

เพื่อที่จะเข้าใจได้ง่ายขึ้นจึงยกตัวอย่างประกอบการอธิบาย ดังนี้

คำสั่ง `j 0xD0200080`  `pc=0xd0000040`  `opcode j=000010`

นำ `D0200080` มาเขียนเป็น *เลขฐานสอง* จะได้ว่า

```
D0200080 = **1101** 0000 0010 0000 0000 0000 1000 00**00**      //4บิตแรก และ 2บิตท้ายออก

         = **0000 10**00 0000 1000 0000 0000 0010 0000
         
         = 0x0808020
```



## HomeWork#2
* **คลิปวีดีโอของการบ้านครั้งที่2**
> [Click Here for HomeWork#2 video](https://youtu.be/GqOXGPJogCU)

* **คำอธิบายเกี่ยวกับการบ้านครั้งที่2**

## HomeWork#3
* **คลิปวีดีโอของการบ้านครั้งที่3**
> [Click Here for HomeWork#3 video](https://youtu.be/lq8xdIlsqn4)

* **คำอธิบายเกี่ยวกับการบ้านครั้งที่3**

## HomeWork#4
* **คลิปวีดีโอของการบ้านครั้งที่4**
>[Click Here for HomeWork#4 video](https://youtu.be/D0uVYcWArPU)

* **คำอธิบายเกี่ยวกับการบ้านครั้งที่4**

## HomeWork#5
* **คลิปวีดีโอของการบ้านครั้งที่5**
> [Click Here for HomeWork#5 video](https://youtu.be/i2Pq82XXq5A)

* **คำอธิบายเกี่ยวกับการบ้านครั้งที่5**

## HomeWork#6
* **คลิปวีดีโอของการบ้านครั้งที่6**
> [Click Here for HomeWork#6 video](https://youtu.be/G1lXcVCzqzM)

* **คำอธิบายเกี่ยวกับการบ้านครั้งที่6**

## HomeWork#7
* **คลิปวีดีโอของการบ้านครั้งที่7**
> [Click Here for HomeWork#7 video](https://youtu.be/J2nr4AUF03M)

* **คำอธิบายเกี่ยวกับการบ้านครั้งที่7**
