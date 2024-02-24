# setup (ทำครั้งเดียว)
1. ติดตั้ง Google Chrome (หากมีแล้วข้าม step นี้ได้)
2. run create-session.cmd โปรแกรมจะให้ Login discord ใน Google chrome เมื่อ login สำเร็จจะได้ไฟล์ session.yaml มาไว้ในโฟลเดอร์

** ไฟล์ session.yaml เก็บข้อมูลละเอียดอ่อนเกี่ยวกับ discord account ของคุณ จึงไม่ควรเปิดให้ใครดู หรือแชร์ไฟล์นี้กับผู้อื่น

# การ run ใช้งาน
1. ใส่ prompt ที่ต้องการไว้ในไฟล์ prompt.txt (ใช้การขึ้นบรรทัดใหม่เผื่อใส่หลาย prompt พร้อมกันได้)
2. run start-generate.cmd หากยังไม่ได้ login โปรแกรมจะให้คุณ login ก่อนในครั้งแรก
3. โปรแกรมจะทำการกรอก prompt ของคุณให้กับ Midjourney ใน Discord ให้ อัตโนมัติ รอจนโปรแกรมทำงานเสร็จสิ้น
3. ไฟล์ภาพที่ได้จะอยู่ใน folder output

# การ Up Scale
1. import รูปเข้า lightroom
2. เลือกรูปทั้งหมดแล้วกด Enhance
3. เมื่อซ้ายบนของรูปที่ Enhance ขึ้นเลข 2 แล้ว ให้เลือกรูปทั้งหมดและกด Export
4. เมื่อขึ้นหน้าต่าง Export ให้ตั้งค่าแบบนี้  
4.1 Export to { Same Folder As Original photo}
4.2 ติ๊กถูกช่อง Put in Subfolder [Final] (พิมพ์ชื่อFolderลงไป)
4.3 Image Setting เลือก 100
4.4 Export ล่างขวา ได้เลย
 
# การใช้โปรแกรมเจนคีย์เวิร์ดฝังไว้ในภาพ
1. หลังจากนำภาพไป upscale เรียบร้อยแล้ว ให้นำโปรแกรม ImageModify ไปไว้ในโฟลเดอร์ที่เก็บภาพ จากนั้นกดเปิดโปรแกรมและ Login User,Pass ที่ท่านสมัครไว้กับเราได้เลย
2. ระบบจะรันเพื่อใส่ Des,Keyword ที่ละไฟล์

# ลบTrade Mark ด้วย imstcoker studio
1. เปิด Imstocker Studio
2. import รูปเข้าโปรแกรม Imstocker Studio
3. เลือกรูปทั้งหมด (จะมี Des, Keyword พร้อมแล้ว)
4. กดเครื่องหมาย + ตรงช่อง Keyword ด้านขวา  จะขึ้นหน้าต่างใหม่มา >>  Add Keyword to all Image 
5. ในหน้าต่าง   Add Keyword to all Image  พิมพ์ Nike และกด Add
6. กดไปที่เมนูที่เป็นรูปดินสอ ขวาล่าง (ใกล้ๆ Suggest Keyword)
7. เลือก Delate Trade Mark
8. กด Save all ซ้ายบน

จบ รูปทั้งหมดพร้อม Upload ส่งแล้วครับ 
Enjoy