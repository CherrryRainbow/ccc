<!DOCTYPE html>
head ข้อมูลเกี่ยวกับเว็บ ทำงานเบื้องหลัง meta, title, etc.
body แสดงข้อมูล
คอมเม้นต์ เขียนโดย <!--comment-->
html element วัตถุใน html
    tag คำสั่ง <tagname> bla bla <tagname>
        h1 h2 h3 ... หัวข้อ
        p พารากราฟ
        b ตัวหนา
        i ตัวเอียง
        hr เส้นคั่น เขียนทีเดียว
        br บรรทัดใหม่
        title ชื่อเพจ
        link เรียกภาษากับเรียกไฟล์
        script เขียน JS code
        meta แปลงภาษา
        div แบ่งช่วงข้อมูลเพื่อความง่ายในการจัด ใช้คู่กับแอนทริบิวต์ id
        a ใช้คู่กับ href = "url" เชื่อมลิงค์
            Full path ที่อยู่ลิงค์เต็มชื่อเต็มยศ
            Relative path ใส่แค่ชื่อไฟล์ในโฟลเดอร์นั้น
                ชื่อไฟล์จริงๆ
                ชื่อโฟลเดอร์เดียวกัน/โฟลเดอร์ยิบย่อย(ถ้ามี)/ชื่อไฟล์
        th หัวข้อ
        thead
        table ตาราง แถวคือ tr คอลัมน์คือ td
        img รูป
        input :
        <input name = "บอกที่อยากใส่" type = "ประเภทข้อมูล(text,
        number,radio,checkbox,file,submit(+value),etc.)
        "required(ต้องกรอก)/disabled(ห้ามกรอก พิมพ์ไม่ได้)>

        form รวม input
        textarea กรอกได้ ขยายได้ กำหนดขนาดได้
        button ปุ่มคล้าย submit แต่ต้องเขียนเหตุการณ์ด้วย
        footer

    attribute เพิ่มเติมวัตถุ ระบุ object
        
        ตัวอย่าง
            <p align = "center">
                align เป็นแอตทริบิวต์ บอกตำแหน่ง
            hr
                width กว้าง
                color สี
            h1
                class ใช้กับทุกออบเจ็กต์
                id ใช้กับ object เดียว
                ทั้งคู่ใช้ระบุออบเจ็กต์
            link
                rel
                href
        src ที่อยู่ไฟล์ที่เอามาเป็นออบเจ็กต์ เช่นใช้คู่กับ img



css(cascading style sheets) เขียน 3 แบบ
    style ส่งผลต่อแท็กนั้นโดยตรง
    ทุกคลาสทุกไอดี มี span อยู่ข้างใน
        span{
            color: สี;
            บลาๆๆ
        }
    แยกไฟล์ ใช้ href ด้วย

    color
    font-family
    จุดบอกคลาส ชาร์ปบอกไอดี ตามด้วยปีกกา ใส่คำสั่งมีโคล่อนกับเซมิโคล่อน

    mergin ขยายชิดขอบ


js
getElementById innerHTML
