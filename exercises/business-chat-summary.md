
# สรุปงานด้วย Business Chat

ในฐานะผู้บริหารฝ่ายขายขององค์กร คุณอาจมีโครงการจริงๆ ที่คุณมีส่วนเกี่ยวข้องในช่วง 30 วันที่ผ่านมา การรับอีเมลที่มากมาย, การประชุม, และการสนทนาออนไลน์จำนวนมากอาจทำให้คุณรู้สึกหนักใจในการจดจำประเด็นสำคัญทั้งหมดที่ถูกพูดถึงในหัวข้อการสื่อสารต่าง ๆ หากมีเครื่องมือ AI ที่สามารถสรุปประวัติการสื่อสารของคุณและให้บทสรุปของกิจกรรมทั้งหมดในเธรดนั้นได้ มันจะช่วยลดความซับซ้อนได้อย่างมาก

คุณจำได้ว่า Business Chat สามารถตรวจสอบกิจกรรมการสื่อสารทั้งหมดใน Outlook และ Teams ให้ข้อมูลสรุป และกำหนดรายการงานที่คุณรับผิดชอบ คุณจึงตัดสินใจใช้ฟีเจอร์นี้เพื่อประหยัดเวลาและความพยายามในการตรวจสอบกิจกรรมการสื่อสารทั้งหมดด้วยตนเอง

ปฏิบัติตามขั้นตอนด้านล่างนี้เพื่อใช้ Business Chat ใน Teams เพื่อสรุปการสื่อสารที่เกี่ยวข้องกับเธรดจริง และนำหลักปฏิบัติที่ดีสำหรับการสร้างคำสั่ง (prompting) เช่น "iterate, iterate, iterate" มาใช้เพื่อเจาะลึกประเด็นสำคัญ

## ขั้นตอน

1. **เลือกหัวข้อหรือโครงการ**:
   - ดูเธรดใน *ทั้ง* กล่องจดหมาย Outlook และ Teams Chat เพื่อหาหัวข้อหรือชื่อโครงการที่ปรากฏในทั้งอีเมลและแชท
   - นำชื่อหัวข้อหรือโครงการที่พบมาใช้ในขั้นตอนถัดไป
2. เปิด Microsoft Edge: เปิดแท็บใหม่และไปที่ https://copilot.microsoft.com
3. เลือกแบบ Work Account
4. ตั้งค่าโหมดการค้นหา: ตรวจสอบสวิตช์ที่ด้านบนของหน้าเว็บ เพื่อเลือกโหมด "Work" เพื่อให้ Copilot เข้าถึงข้อมูล Microsoft 365 ของคุณ


5. **ป้อนคำสั่งแรก**:
   - ในช่องพร้อมท์ที่ด้านล่างของหน้าต่าง Copilot ป้อนคำสั่งต่อไปนี้โดยแทนที่ `{หัวข้อ/โปรเจคที่เราเลือก}` ด้วยชื่อหัวข้อหรือโครงการที่คุณเลือก:

     ```
     เนื้อหางานในรอบ 30 วันที่เกี่ยวข้องกับ {หัวข้อ/โปรเจคที่เราเลือก} โดยดึงข้อมูลจาก email, chat, และ files ต่างๆ 
     ```
     ตัวอย่างของพล
     ```
     เนื้อหางานในรอบ 30 วันที่เกี่ยวข้องกับ wisepaq โดยดึงข้อมูลจาก email, chat, และ files ต่างๆ โดยไม่ต้องแสดงชื่อบริษัทหรือองค์กรอื่นในผลลัพธ์
     ```

   - คลิกไอคอนส่ง (Send)

6. **ตรวจสอบผลลัพธ์**:
   - อ่านข้อมูลสรุปที่ Copilot ให้มา
   - สังเกตตัวเลือกที่ปรากฏเหนือช่องพร้อมท์ที่เกี่ยวข้องกับอีเมล การประชุม และแชทที่สรุปไว้
   - เลือกตัวเลือกใดตัวเลือกหนึ่งเพื่อดูการตอบสนองของ Copilot

7. **เจาะลึกข้อมูลเพิ่มเติม**:
   - หากมีตัวเลือกเพิ่มเติมที่เกี่ยวข้องกับตัวเลือกก่อนหน้า ให้เลือกตัวเลือกใหม่
   - สังเกตว่าตัวเลือกที่กำหนดไว้ล่วงหน้าเปลี่ยนไปอย่างไร และให้ไอเดียหรือ action ที่คุณไม่เคยนึกถึงหรือไม่

8.  **สร้างรายการงานที่ต้องรับผิดชอบ**:
    - ป้อนคำสั่งต่อไปนี้เพื่อให้ Copilot สร้างรายการงานที่คุณรับผิดชอบจากอีเมล การประชุม และแชท:
  
        ```
        Based on the information that you synthesized from my emails, meetings, and chats, create a list of action items that I'm responsible for.
        ```
        ภาษาไทย

        ```
        จากข้อมูลที่คุณสรุปจากอีเมล, การประชุม, และแชทของฉัน กรุณาสร้างรายการงานที่ฉันต้องรับผิดชอบ
        ```

    - คลิกไอคอนส่ง (Send)

9.  **จัดลำดับความสำคัญของงาน**:
   - ป้อนคำสั่งต่อไปนี้เพื่อให้ Copilot จัดลำดับความสำคัญของรายการงานตามความสำคัญ:

     ```
     Please rank these action items by order of importance.
     ```
        ภาษาไทย
        ```
        กรุณาจัดลำดับรายการงานเหล่านี้ตามลำดับความสำคัญ
        ```

   - ตรวจสอบผลลัพธ์และเข้าใจข้อจำกัดของ Copilot ในการจัดลำดับงานที่ขึ้นอยู่กับบริบทและลำดับความสำคัญของโครงการ

10. **ปรับคำสั่งตามข้อจำกัดของ Copilot**:
   - เน้นรายการงานที่เกี่ยวข้องกับบุคคล การประชุม หรือหัวข้อที่สำคัญสำหรับคุณโดยใช้คำสั่งต่อไปนี้:

     ```
     In all of the action items that you found for me, which ones involve {person/meeting/topic name of your choice}?
     ```
     ภาษาไทย
        ```
        ในรายการงานทั้งหมดที่คุณพบสำหรับฉัน มีใครที่เกี่ยวข้องกับงานในโครงการบ้าง?
        ```


11. **ตรวจสอบและถามคำถามเพิ่มเติม**:
   - ตรวจสอบรายการงานที่ Copilot สร้างขึ้น
   - ถามคำถามเพิ่มเติมหรือขอให้ Copilot ทำงานอื่น ๆ ที่คุณสนใจเกี่ยวกับโครงการหรือหัวข้อนั้น

## สรุป

ในการใช้ Business Chat ใน Teams คุณสามารถสรุปกิจกรรมการสื่อสารทั้งหมดที่เกี่ยวข้องกับเธรดจริง และสร้างรายการงานที่ต้องรับผิดชอบจากอีเมล การประชุม และแชท โดยใช้ข้อมูลที่ Copilot สรุปให้ ด้วยข้อมูลนี้ คุณสามารถวางแผนงานการทำงานของคุณในรอบ 30 วันถัดไปได้อย่างมีประสิทธิภาพ