# MiniPrject_Mg400 Overview Code
 650610828 นาย จักรพงศ์ วงศ์วิวัฒน์ธนะ<br> 650610829 นาย จินตพัฒน์ ตาอ้าย <br>650610853 นาย ภูรินท์ ภัทโรวาสน์
#
# 🤖Feature 
- สื่อสารกับ Mg400 ผ่าน TCP Socket
- ตรวจจับวัตถุจากกล้องโดยใช้ HSV threshold และฟิลเตอร์ภาพ
- แปลงพิกัดกล้องเป็น world coordinates
- แก้ไขความบิดเบี้ยวของภาพด้วย radial distortion
- แสดงภาพ Annotated Output และ Combined Mask
## hsv_config.json 
- HSV ranges ของแต่ละสี
- ประเภท Morph Operation
- ขนาด kernel และจำนวนรอบ
- ค่าการบิดเบี้ยวของเลนส์ (Distortion k)
#
# User Manual 
1. Set IP Ethernet LAN เพื่อให้ Dobot สามารถหาเจอ
2. Run Setup.py เพื่อ Tune HSV และ Morphology ผ่าน GUI
3. Press S to save Config of HSV and Morphology to hsv_config.json
4. Use Dobot.studio to run Mg400 by import folder Dobot_import
5. Set Pos of Mg400 to the Pos like to do
6. Calibate position from dobot studio in Client.py to set world co-ordinate
7. Run code in dobot studio
8. Run Client.py Choose set color in GUI bar and control Mg400  to start process
9. Enjoy!
#

