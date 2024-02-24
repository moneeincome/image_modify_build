# setup (ทำครั้งเดียว)
1. ติดตั้ง Google Chrome (หากมีแล้วข้าม step นี้ได้)
2. run create-session.cmd โปรแกรมจะให้ Login discord ใน Google chrome เมื่อ login สำเร็จจะได้ไฟล์ session.yaml มาไว้ในโฟลเดอร์

** ไฟล์ session.yaml เก็บข้อมูลละเอียดอ่อนเกี่ยวกับ discord account ของคุณ จึงไม่ควรเปิดให้ใครดู หรือแชร์ไฟล์นี้กับผู้อื่น

# การ run ใช้งาน
1. ใส่ prompt ที่ต้องการไว้ในไฟล์ prompt.txt (ใช้การขึ้นบรรทัดใหม่เผื่อใส่หลาย prompt พร้อมกันได้)
2. run start-generate.cmd หากยังไม่ได้ login โปรแกรมจะให้คุณ login ก่อนในครั้งแรก
3. โปรแกรมจะทำการกรอก prompt ของคุณให้กับ Midjourney ใน Discord ให้ อัตโนมัติ รอจนโปรแกรมทำงานเสร็จสิ้น
3. ไฟล์ภาพที่ได้จะอยู่ใน folder output