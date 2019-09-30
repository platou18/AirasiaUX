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

![alt text](https://raw.githubusercontent.com/platou18/AirasiaUX/master/pic1.png)
