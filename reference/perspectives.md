# Perspectives — 2026-07-11

## 1. Apple ฟ้อง OpenAI ขโมยความลับทางการค้า

**อาจารย์ (มหาวิทยาลัย):** คดีนี้เป็นกรณีตัวอย่างชั้นดีสำหรับสอนเรื่อง Trade secret law ในยุค AI race — นักศึกษาควรเข้าใจว่าความรู้ที่ "อยู่ในหัว" กับเอกสารลับที่ถ่ายโอนออกมาเป็นคนละเรื่อง และ AI recruitment war กำลังทำให้เส้นแบ่งนี้เลือนรางมากขึ้นเรื่อยๆ
**ผู้เชี่ยวชาญด้าน AI:** การที่ OpenAI มี Chief Hardware Officer และเน้น On-device AI บ่งชี้ว่า Edge AI เป็น Strategic frontier ถัดไป ผลพวงทางกฎหมายของคดีนี้อาจบังคับให้ AI companies ทั้งอุตสาหกรรมต้องเพิ่ม Trade secret firewall ในกระบวนการ Hiring
**โปรแกรมเมอร์มืออาชีพ:** ทุกคนที่ย้ายจาก Big Tech มา AI startup ควรทบทวน NDA และ IP assignment agreement อีกครั้ง — คดีนี้พิสูจน์ว่าบริษัทเดิมพร้อมฟ้อง และระบบ Digital forensics ตรวจหลักฐานการดาวน์โหลดไฟล์ได้แม้นานหลายเดือน

## 2. SK Hynix IPO $26.5 พันล้าน สูงสุดในประวัติศาสตร์

**อาจารย์ (มหาวิทยาลัย):** IPO นี้เป็นตัวอย่างของ "AI infrastructure as a macro signal" — การที่นักลงทุนสหรัฐยอมจ่าย premium ให้บริษัทชิปเกาหลีบ่งชี้ว่าตลาดกำหนดราคา AI boom ในระดับ hardware layer ไม่ใช่แค่ software หรือ model
**ผู้เชี่ยวชาญด้าน AI:** SK Hynix ครอง 60% HBM market share หมายความว่า bottleneck ของ AI training scale ในระยะ 2-3 ปีข้างหน้าอยู่ที่ supply chain นี้โดยตรง หากโรงงานใหม่เปิดได้ตามแผน compute cost จะลดลงเร็วกว่าที่ตลาดคาด
**โปรแกรมเมอร์มืออาชีพ:** API pricing ของทุก AI provider ผูกกับ HBM cost ทางอ้อม — ถ้า SK Hynix ขยาย capacity ได้ตามแผน token cost ของ frontier models จะลดลง เปิด Use case ใหม่ที่ตอนนี้ยัง cost-prohibitive อยู่

## 3. OpenAI มุ่งสู่ตลาดครัวเรือน

**อาจารย์ (มหาวิทยาลัย):** งานวิจัยที่พบว่าผู้ปกครองประเมิน AI usage ของลูกต่ำกว่าความเป็นจริงถึง 11 percentage points เป็นสัญญาณให้โรงเรียนเร่ง AI literacy ตั้งแต่ระดับประถม ไม่ใช่รอให้มหาวิทยาลัยจัดการ
**ผู้เชี่ยวชาญด้าน AI:** การมี dedicated PM สำหรับ Family segment จะสร้าง product surface ที่มี Safety constraints เข้มงวดกว่า consumer product ทั่วไป และน่าจับตาว่า Parental controls ที่ OpenAI พัฒนาจะ shape industry standard สำหรับ AI for children หรือไม่
**โปรแกรมเมอร์มืออาชีพ:** Age-verification และ Parental consent API กำลังจะกลายเป็น requirement ใหม่สำหรับ consumer AI apps — ออกแบบ Architecture ให้รองรับ age-gating ตั้งแต่ตอนนี้ดีกว่าต้อง retrofit ภายหลัง

## 4. Instagram ถอนฟีเจอร์ AI สร้างคอนเทนต์จากบัญชีสาธารณะ

**อาจารย์ (มหาวิทยาลัย):** กรณีนี้สอนเรื่อง Default settings ethics ได้ดีเยี่ยม — การเลือก opt-out แทน opt-in เป็นการ externalize cost ไปยังผู้ใช้ที่ไม่ได้ขอ ซึ่งขัดกับหลัก Informed consent โดยสิ้นเชิง
**ผู้เชี่ยวชาญด้าน AI:** ความเร็วในการถอนฟีเจอร์ชี้ว่า Meta ประเมิน Social blowback ต่ำเกินไปในช่วง Product review — ทีม AI Ethics ต้องทำงานคู่ขนานกับ Product launch ไม่ใช่ตาม
**โปรแกรมเมอร์มืออาชีพ:** Default permission model สำหรับ Generative AI ที่ใช้ User content ต้องเป็น opt-in เสมอ — เรียนรู้จากกรณีนี้ก่อน Ship ฟีเจอร์ใดที่แตะ User-generated content

## 5. Notion Agents แอปแยก iOS

**อาจารย์ (มหาวิทยาลัย):** Notion Agents เป็นตัวอย่างของ "Agentic layer on top of knowledge base" ที่นักศึกษาควรเข้าใจเป็น design pattern ที่จะเห็นบ่อยขึ้นเรื่อยๆ — ความรู้อยู่ใน Notion, Agent อยู่บน top, ผู้ใช้ interact ผ่าน Natural language
**ผู้เชี่ยวชาญด้าน AI:** การที่ Notion รองรับ GPT, Claude, และ Gemini พร้อมกันโดยผู้ใช้เลือกได้บ่งบอกทิศทาง — "Model-agnostic orchestration" จะเป็น competitive differentiator สำหรับ productivity tools ในปีหน้า
**โปรแกรมเมอร์มืออาชีพ:** Standalone app สำหรับ Agent mode แยกจากแอปหลักเป็น UX pattern ที่น่าจับตา — ตรวจสอบว่า Notion Agents มี webhook หรือ event trigger ให้ใช้หรือไม่ เพราะจะเปลี่ยนวิธี Build Notion-native automation อย่างมีนัยสำคัญ
