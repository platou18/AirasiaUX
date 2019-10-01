# Airasia Kiosk User Interface
## Kiosk self-check in ของทางสายการบินแอร์เอเชีย

คีออสเช็คอินเป็นหนึ่งในเทคโนโลยีที่ทางแอร์เอเชียมีไว้สำหรับผู้โดยสาร โดยเป็นหนึ่งในทางเลือกในการเข้าเช็คอินและโหลดสัมภาระสำหรับผู้โดยสาร โดยการใช้เลือกให้บริการคีออสสำหรับเช็คอินเป็นหนึ่งในวิธีการลดภาระและเพิ่มความรวดเร็วในการเช็คอินเนื่องจากใช้ระยะเวลาในการใช้งานที่สั้นเพียง 60 วินาทีทั้งยังสามารถเข้าเช็คอินและรับบอร์ดิ้งพาสได้ล่วงหน้าถึง 14 วัน

**การใช้งานเครื่องคืออสจะมีฟังชั่นการใช้งานได้ 3 แบบคือ**
1.	เช็คอิน
2.	พิมบอร์ดิ้งพาสอีกครั้ง
3.	พิมพ์ป้ายติดสัมภาระ

โดยมีรายละเอียดการใช้งานดังนี้

**การเช็คอิน**

จะทำได้โดยมี 3 ทางเลือกในการใช้งาน ได้แก่
-	พิมพ์หมายเลขที่นั่งจอง หรือ booking number
-	สแกนกำหนดการเดินทา หรือ itinerary
-	ใส่บัตร big card
โดยมีเงื่อนไขการใช้งานคือ 14 วัน - 1 ชั่วโมง ก่อนเวลาของเที่ยวบินนั้นๆ โดยปกติสามารถเช็คอินได้สำหรับสนามบินที่จะทำการเดินทางเท่านั้นไม่สามารถใช้ทำสนามบินอื่นได้ โดยมีข้อยกเว้นเป็นตั๋วไป - กลับ โดยสามารถเช็คอินและพิมพ์ตั๋วทั้งขาไปและขากลับได้หากอยู่ในช่วงระยะเวลาเช็คอินของ คีออสเช็คอิน และหลังจากหน้าเมนูเช็คอินจะเป็นการพิมพ์ป้ายติดสัมภาระ


**การพิมพ์บอร์ดดิ้งพาสอีกครั้ง**

จะทำได้โดยมี 2 ทางเลือกในการใช้งาน ได้แก่
-	พิมพ์หมายเลขที่นั่งจอง หรือ booking number
-	สแกนบาร์โค้ด 2D
เหมาะสำหรับผู้โดยสารที่ต้องการพิมพ์บอร์ดิ้งพาสจากการเช็คอินจากทางเลือกอื่นๆมาเช่นผู้โดยสารที่เช็คอินผ่านเว็บ ผู้โดยสารที่เช็คผ่านแอพพลิเคชั่นแอร์เอชีย และผู้โดยสารที่ต้องการพิมพ์บอร์ดิ้งพาสอีกครั้งกรณีสูญหาย โดยมีข้อจำกัดในการพิมพ์คือ 2 ครั้ง

**การพิมพ์ป้ายติดสำภาระ**

จะทำได้โดยมี 2 ทางเลือกในการใช้งาน ได้แก่
-	พิมพ์หมายเลขที่นั่งจอง หรือ booking number
-	สแกนบัตรผ่านขึ้นเครื่อง
สำหรับผู้โดยสารที่ซื้อน้ำหนักกระเป๋ามาก่อนและไม่ใช่ผู้โดยสารที่ซื้อตั๋วโดยสารแบบข้าราชการ

**ขั้นตอนการใช้งานเครื่องคีออสเช็คอินสามารถแสดงเป็น flow-chart ได้ดังนี้**

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Chart1.png)

**ข้อจำกัดในการใช้งานเครื่องคีออสเช็คอิน**

-	ผู้โดยสารที่เดินทางในเส้นทางสหรัฐอเมริกา
-	ผู้โดยสารที่เลือกที่นั่งในแถวทางออกฉุกเฉินสำหรับเที่ยวบินแอร์เอเชียรหัส DJ
-	มีข้อจำกัดในการเคลื่อนไหวร่างกายหรือต้องการความช่วยเหลือพิเศษ
-	อายุต่ำกว่า 16 ปีและเดินทางคนเดียว
-	เดินทางพร้อมกับทารกอายุไม่เกิน 8 วัน
โดยผู้โดยสารที่มีคุณสมบัติต่อไปนี้ยังคงสามารดำเนินการเช็คอินด้วยตัวเองได้แต่จำเป็นต้องแสดงตัวต่อพนักงานภาคพื้น :
-	กำลังตั้งครรภ์
-	มีอาการเจ็บป่วย

## การสำรวจปัญหา
จากการสำรวจและการใช้งานเครื่องคีออสเช็คอินพบว่า UI หรือ User Interface คีออสเช็คอินของสายการบินแอร์เอเชียพบว่ามีปัญหาและข้อบกพร่องทั้งในด้านการออกแบบและการใช้งานดังต่อไปนี้
-	การออกแบบ UI ที่ผิดพลาดไม่ตรงตามหลักที่ถูกต้อง
-	รูปแบบ UI ที่ล้าสมัยและไม่มีการปรับปรุง
-	มีข้อมูลที่ทำให้สับสนจนอาจทำให้ใช้งานผิดพลาดได้
-	ไม่มีข้อมูลในการใช้งานที่ชัดเจนและเข้าถึงง่าย
-	มีการลิงค์หน้าเมนูผิดทำให้การทำงานของเครื่องมีความผิดพลาดละอาจทำให้เสียเวลาได้

**การออกแบบ UI โดยรวมของเครื่อง Kiosk เช็คอินอัตโนมัติ**

รูปแบบโดยรวมจะใช้พื้นหลังสีขาว ประดับด้วย Pattern รูปวงกลมซ้อน และ โลโก้ของทางแอร์เอเชีย

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Pic1.png)

และประกอบไปด้วย UI ปุ่มแบบพื้นฐานที่ใช้ไปในทุกหน้าเมนูและส่วนต่าง ๆของเครื่องโดยจะใช้รูป สี่เหลี่ยมตัดขอบในการเข้าถึงเมนูหรือฟังชั่นหลัก และ ใช้รูปวงกลมในการ navigate เมนูต่าง ๆ อาทิเช่น ย้อนกลับ ยกเลิก ยืนยัน

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Pic2.PNG)

โดยปัญหาของการออกแบบสามารถแบ่งได้หลายส่วน ดังนี้

**การออกแบบ UI ในหน้าเมนูพิมพ์หมายเลขที่นั่งจอง**

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Pic3.png)

มีการใช้คีย์บอร์ดแบบ Qwerty มีปุ่มฟังชั่นเพิ่มเติมคือ Backspace และ Clear ซึ่งปุ่มเหล่านี้ผู้ใช้งานจะคุ้นเคยเพราะนิยมใช้ ทั้ง คอมพิวเตอร์และโทรศัพท์มือถือ

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Pic4.png)

ปัญหาของการออกแบบบนคีออสเกิดจากการวาง Backspace และ Clear ไว้ด้านล่างใกล้กับปุ่มย้อนกลับและยืนยัน บ่อยครั้งเกิดปัญหาผู้ใช้งานกด Clear แทนที่จะยืนยันเพื่อใช้งานต่อไปทำให้เสียเวลาเพิ่มมากขึ้นในการพิมพ์ใหม่อีกครั้ง

**การออกแบบ UI ในการกดย้อนกลับและยกเลิกในหน้าเมนู**

มีการวางปุ่มย้อนกลับและยกเลิกไว้ไม่ทั่วถึงในหน้าเมนูต่าง ๆ

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Pic5.png)

เมื่อเลือกเข้าเมนู เช็คอินต่าง ๆ ไม่มีปุ่มย้อนกลับไปเมนูก่อนหน้ากรณีที่กดผิด การกดปุ่มยกเลิกแทนที่จะย้อนไปหน้าเมนูหลักกลับเป็นการยกเลิกการทำงานทั้งหมดย้อนกลับไปหน้าที่แสดงสไลด์แทนทำให้เมื่อต้องการยกเลิกหรือย้อนไปเลือกเมนูอื่น ๆมีการใช้เวลาที่มากขึ้น

### Flow Chart ต่อไปนี้แสดงถึงขั้นตอนการกดยกเลิกและย้อนกลับของเมนูต่าง ๆ
**เมนูเช็คอิน**
![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Chart2.png)

**เมนูพิมพ์บอร์ดิ้งพาสใหม่อีกครั้ง**
![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Chart3.png)

**เมนูพิมพ์ป้ายติดการเป๋าสัมภาระ**
![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Chart4.png)

เมื่อดูจาก flow chart ข้างต้น จะเห็นได้ว่ามีข้อบกพร่องในการลิงก์หน้าเมนูตามปกติเมื่อกดย้อนกลับจะกลับไปหน้าก่อนหน้า แต่ในเมนูของการพิมพ์ป้ายติดกระเป๋า > สแกนบอร์ดดิ้งพาส เมื่อกดย้อนกลับจะไปขึ้นที่หน้าเมนูของการเช็คอินแทนที่จะเป็นเมนูของการพิมพ์ป้ายติดกระเป๋า

**การใช้เลือกใช้ภาษาที่เข้าใจยาก**

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/Pic6.png)

ในหน้าเมนูนี้มีการใช้ภาษาที่ไม่ถูกต้องหรือยากแก่การเข้าใจผู้ใช้งานส่วนมากไม่เข้าใจคำว่าบาร์โค้ด 2D และจากการสำรวจจำเป็นต้องใช้ QR code จากมือถือ หรือ Web check-in ในการแสกนเพื่อพิมพ์บอร์ดดิ้งพาสจึงจะสามารถใช้งานได้ และในหน้าเมนูเดียวกันในภาษาญี่ปุ่นมีข้อมูลที่ถูกต้อง ซึ่งเป็น QR code หรือ Web check-in barcode ต่างจากภาษาอื่น ๆ ที่ยังเป็นบาร์โค้ด 2D

**การเข้าถึงข้อมูลการใช้งานหรือข้อจำกัดการใช้งานของเครื่องคีออส**

เครื่องคีออสเช็คอินเมื่อไม่ได้ใช้งานจะแสดงสไลด์โฆษณาต่าง ๆ การใช้งานคีออส และ ข้อจำกัดในการใช้งาน แสดงอยู่โดยตลอดโดยสลับเปลี่ยนไปทุก ๆ 30 วินาที แต่เมื่อคลิกที่หน้าจอเพื่อเริ่มใช้งานกลับไม่มีข้อมูลในการใช้งาน เพื่อผู้โดยสารสามารถอ่านข้อมูลและข้อจำกัดวิธีการใช้งานได้โดยละเอียด

ตัวอย่างการแก้ไข UI ตามที่ได้ระบุข้างต้น https://platou18.github.io/AirasiaUX/index.html
