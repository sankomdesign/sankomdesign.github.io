Element
==========

Element. คือส่วนที่ประกอบขึ้นเป็น User interface ผู้ใช้งานมีความคุ้นเคยกับ User interface จากประสบการณ์ที่ผ่านมาของพวกเขา โปรดเลือกใช้งานด้วยความระมัดระวัง โดยคำนึงถึงความสม่ำเสมอและสามารถคาดเดาได้ เพื่อช่วยให้เป้าหมายของผู้ใช้งานนั้นเสร็จแบบมีประสิทธิภาพและได้รับความพึงพอใจ

##### 1. Input controls
- Button, Data field, List-Box, Dropdown list

##### 2. Selection controls
- Toggles, Radio-button, Checkbox
  
##### 3. Navigational components
- Breadcrumb, Slider, Search, Pagination, tag

##### 4. Informational components
- Tool-tip, icon, Progress bar, Notification, Message Box, Modal

##### 5. Container
- Accordion


## Atomic design concept
...



## Button

### Text Label

เป็นคำพูดที่ใช้อธิบายการทำงานของปุ่มแบบสั้นๆ เพื่อให้เข้าใจและสามารถคาดเดาได้ว่าจะเกิดอะไรขึ้นเมื่อกดปุ่ม และใช้ตัวอักษรพิมพ์ใหญ่ ถ้าหากเป็นภาษาอังกฤษ เพื่อให้เห็นถึงความแตกต่าง

ควรใช้คำอธิบายภายในหนึ่งบรรทัด ไม่ควรทำเป็นสองบรรทัด

![Test](images/button/Text-Label-Case.jpg)

### Text Button

เป็นปุ่มที่มีความเด่นน้อยที่สุดในบรรดาปุ่มทั้งหมด ใช้งานเมื่ออยู่ร่วมกันกับ Cards หรือ Dialogs ต่างๆ

![Test](images/button/Text-Button.jpg)

### Outline Button

เป็นปุ่มที่มีความเด่นปานกลาง ใช้งานเมื่อที่ใช้เพื่อให้เป็นตัวเลือกรองมาจากตัวเลือกหลัก เพื่อให้มีการตัดสินใจบางอย่าง

![Test](images/button/Outline-Button.jpg)

### Contained Button

เป็นปุ่มที่มีความเด่นมากที่สุดในบรรดาปุ่มทั้งหมด ใช้งานเพื่อเป็น Call to Action หลัก

![Test](images/button/Contained-Button.jpg)

### Toggle Button

เป็นปุ่มที่ใช้สำหรับเปิดหรือปิด Function ต่างๆ ซึ่งมีผลทันทีที่กดปุ่ม

![Test](images/button/Toggle-Button.jpg)


## Selection Control

### Checkbox

- เมื่อต้องการเลือกหนึ่งหรือหลายๆสิ่งจากหลายการ
- เมื่อมีตัวเลือกย่อยในหัวเรื่อง
- เมื่อต้องการเปิด-ปิดตัวเลือก (Desktop)

![Test](images/input-control/Checkbox-Case.jpg)
![Test](images/input-control/Select-all-Case.jpg)


### Radio

- เลือกเพียงหนึ่งอย่างจากสิ่งที่มีทั้งหมด
- เห็นตัวเลือกทั้งหมดพร้อมๆกัน

![Test](images/input-control/Radio-Case.jpg)


### Switch
- เมื่อต้องการเปิด-ปิดสิ่งใดๆ (Tablet, Mobile)
- เมื่อต้องการเปิด-ปิดสิ่งใดๆ ซึ่งมีผลทันที

![Test](images/input-control/Switch-Case.jpg)

### State

![Test](images/input-control/State.jpg)


### Speces

![Test](images/input-control/Specs.jpg)

## Modals
เป็นสิ่งที่ไว้สำหรับแจ้งข้อมูลบางอย่างที่มีความสำคัญมากแก่ผู้ใช้งาน เพื่อให้ผู้ใช้งานตัดสินใจบางอย่าง

### Anatomy
![Test](images/modals/Modal-Anatomy.jpg)
1. Container
2. Title (Optional)
3. Supporting Text
4. Buttons

### Simple Modal
เป็น Modal อย่างง่าย ใช้เพื่อเสนอ Content บางอย่างที่มีความสำคัญแก่ผู้ใช้งาน อาจจะเป็นตัวเลือกที่เมื่อผู้ใช้งานเลือกแล้วมีผลทันที
![Test](images/modals/Simple-Modal.jpg)

### Alert Modal
เป็น Modal สำหรับแจ้งเตือนผู้ใช้งานให้ทำการตัดสินใจ จึงจะสามารถทำรายการต่อไปได้
![Test](images/modals/Alert-Modal.jpg)

### Confirmation Modal
เป็น Modal สำหรับให้ผู้ใช้งานตัดสินใจเลือกบางอย่าง จากสิ่งที่ Modal แสดงผลออกมา
![Test](images/modals/Confirmation-Modal.jpg)
 
 ### Speces
 
 Modal Desktop
![Test](images/modals/Modal-Desktop-Spec.jpg)

 Modal Mobile
 ![Test](images/modals/Modal-Mobile-Spec.jpg)

 ## Snack Bar
เป็นสิ่งที่ไว้สำหรับแจ้งข้อมูลบางอย่างที่มีความสำคัญไม่มากแก่ผู้ใช้งาน อาจเป็นการแจ้งให้ทราบถึงการเปลี่ยนแปลง

### Anatomy
 ![Test](images/snack-bar/Snack-Bar-Anatomy.jpg)
1. Text Label
2. Container
3. Button (Optional)

การใช้ Icon ประกอบสามารถทำได้ แต่ควรใช้อย่างระมัดระวังและหลีกเลี่ยงกรณีที่ Icon ไม่สื่อความหมายไปในทิศทางเดียวกันกับข้อความ
![Test](images/snack-bar/Snack-Bar-Text-Label-1.jpg)

ไม่ใช้ Contained Button ร่วมกับ Snack Bar เนื่องจากมี Contrast มากเกินความจำเป็น แนะนำให้ใช้ Text Button ร่วมกับสีที่แตกต่างจากข้อความก็เพียงพอแล้ว
![Test](images/snack-bar/Snack-Bar-Button-2.jpg)

กรณีที่ Container มีขนาดจำกัด Text Label สามารถมีได้มากกว่า 1 บรรทัด หรือถ้าหาก Text Label ของปุ่มมีความยาว ก็สามารถขึ้นบรรทัดใหม่ได้เช่นกัน
![Test](images/snack-bar/Snack-Bar-Button-1.jpg)

Snack Bar ไม่ควรมีมากกว่า 1 Action เนื่องจากเป็นสิ่งที่ไว้สำหรับแจ้งให้ผู้ใช้งานรู้ถึงข้อมูล ไม่ได้เป็นสิ่งที่ให้ผู้ใช้งานตัดสินใจ
![Test](images/snack-bar/Snack-Bar-Button-3.jpg)

ตัว Snack Bar อาจไม่มีปุ่มให้ผู้ใช้งานกดก็ได้ อาจเป็นการแจ้งผู้ใช้งานให้ทำการรอให้ระบบทำงานแบบอัตโนมัติ
![Test](images/snack-bar/Snack-Bar-Delay.jpg)

### Speces
![Test](images/snack-bar/Snack-Bar-Spec.jpg)