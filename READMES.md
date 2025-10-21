# Android App Mover

ย้ายแอป Android ไปยัง SD/แฟลชเมมโมรี (Adoptable Storage) และส่งข้อมูลไปยัง Cloud (cloud-android-web) โดยไม่ต้อง root

## โครงสร้าง
android-app-mover/ │ ├── move_app_to_memory_check.sh   # สคริปต์หลัก ├── scripts/                      # สคริปต์ย่อย ├── logs/                         # บันทึกการย้ายแอป └── integrations/ └── cloud-android-web/       # เชื่อมต่อระบบ cloud
