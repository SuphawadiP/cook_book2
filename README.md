# Captive Portal Example

## การเลือก Example IDF

![image](https://github.com/user-attachments/assets/26ce7477-2488-46a5-82ae-0502e6649cc0)

ขั้นตอนการเลือก Example IDF

1. เลือก ESP-IDF
2. เปิดโปรแกรมตัวอย่าง captive_portal
3. เลือก captive_portal
4. เลือก Create project using example captive_portal
5. build, flash และ monitor โปรแกรม

### ผลลัพธ์

โดยการทำงานของ Example นี้คือทำให้ esp32 เป็น Captive Portal และเป็น Access Point โดยจะแสดงหน้าเข้าสู่ระบบกับอุปกรณ์ที่มาเชื่อมต่อ

6. เชื่อมกับ esp32_ssid -> จะขึ้นหน้า root.html เมื่อนำอุปกรณ์เชื่อมต่อเข้าไปที่เครือข่าย
   
![image](https://github.com/user-attachments/assets/92036f1b-c04c-423c-ae6b-62ddf5ffb7b5)


### การแก้ไข
* สามารถแก้ไขชื่อและรหัส Access Point โดยการกด menuconfig
* Example Configuration และเปลี่ยนตามต้องการแล้วกด save

![image](https://github.com/user-attachments/assets/c2fe6ea2-f310-41c2-8ee8-0b1931c3e96e)

* สามารถแก้ไขหน้า root.html ได้
* build, flash และ monitor โปรแกรมใหม่อีกครั้ง

![Screenshot 2024-11-10 004558](https://github.com/user-attachments/assets/ad752395-9a27-4d54-a539-e730c008ad7f)


### สรุปผลการทดลอง

* การทดลอง captive_portal Example บน ESP32 เป็น Captive Portal และเป็น Access Point โดยจะแสดงหน้าเข้าสู่ระบบกับอุปกรณ์ที่มาเชื่อมต่อเมื่ออัปโหลดโค้ดสำเร็จ 
