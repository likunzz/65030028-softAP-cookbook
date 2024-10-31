# แนวทางการทำงาน ESP32 ESP32_ESP-IDF_WiFi-AP cook book
## 1.ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
เลือกโปรเจค Wi-Fi SoftAP Example จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/7ba204f1-c7f0-4e73-b29b-97ec13831153)

## 2.ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร
สามารถไปที่ idf.py menuconfig ที่ example config เพื่อตั้งค่า WiFi SSID/password

![image](https://github.com/user-attachments/assets/218b1d86-2976-4f74-b3d8-d99367e6849d)


## 3. แสดงขั้นตอนการทำ project
หลังจากแก้ไขแล้วให้กด build จะได้รหัสไวไฟและรหัสผ่านตามที่เขียน
![image](https://github.com/user-attachments/assets/f2db6dcb-b7ad-42db-8e7a-d929c3294ed0)

ลองเชื่อมwifi
![image](https://github.com/user-attachments/assets/30862494-16a7-4f09-8c0a-15d03d70573f)

## 4. แสดงผลการทำ project
เมื่อกดเชื่อมผ่านมือถือแล้วจะแสดงค่า
![image](https://github.com/user-attachments/assets/45cd89a9-e046-47de-9835-8fff2147f64d)

เมื่อยกเลิกเชื่อมต่อ

![image](https://github.com/user-attachments/assets/a834f25c-2cf6-44a1-b3ab-da49ba7dcabb)

## 5. สรุปผลการทำ project
โปรเจคนี้ทำงานเป็น SoftAP ซึ่งช่วยให้ อุปกรณ์อื่นๆ สามารถเชื่อมต่อมาที่ ESP32 ได้เหมือนกับการเชื่อมต่อกับเครือข่าย Wi-Fi
