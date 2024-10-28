# Practice System Login-2 (common)

common จะทำการแปลงออบเจ็กต์เป็น json ให้ แล้วส่งไปยัง kafka เมื่อ consumer ดึงข้อมูลจะทำการแปลงค่ากลับ

## Structure Modules

* login (server backend, producer)
* email (consumer)
* common ทำหน้าที่เป็นตัวกลางเพื่อแชร์ข้อมูล email ให้กับ kafka

## Structure

    └── src/main/java/com/login

        /common
        ├── CommonApplication.java
        └── EmailRequest
