# Product-OTA-DeskCompanion
ขั้นตอนออกเวอร์ชันใหม่ (ใช้ซ้ำได้ทุกครั้ง)
เพิ่ม FW_VERSION ใน config.h
กด ✓ Build อย่างเดียว
อัปโหลด .pio\build\cyd28\firmware.bin ขึ้น GitHub ทับไฟล์เดิม
รอสักครู่ให้แคชของไฟล์ firmware หมด
แก้ "version" ใน manifest.json ให้ตรงกับ FW_VERSION
บอร์ดกด Check update แล้ว Update OTA
