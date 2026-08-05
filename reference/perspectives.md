# Perspectives — 2026-08-05

## 1. Google DeepMind: Demis Hassabis ก้าวลงจาก CEO สู่ Chairman และ Alphabet's Chief Scientist

**อาจารย์ (มหาวิทยาลัย):** การเปลี่ยนผ่านครั้งนี้เป็น case study คลาสสิกของ "founder transition" ที่ควรเรียนรู้ — การสร้างตำแหน่ง "Alphabet's Chief Scientist" เป็นกลไกที่ Alphabet ใช้รักษา founder vision ไว้ในองค์กรขนาดใหญ่โดยไม่ขัดขวาง execution ใน operational layer; เปรียบได้กับ Steve Jobs กลับสู่บทบาท product visionary ที่ Apple
**ผู้เชี่ยวชาญด้าน AI:** Koray Kavukcuoglu เป็นสถาปนิกของ Gemini architecture จริงๆ — การขึ้นมานำ DeepMind อย่างเป็นทางการน่าจะหมายถึง product velocity ที่เพิ่มขึ้น; Hassabis ในบทบาท "Alphabet's Chief Scientist" มี leverage เหนือ AI strategy ทั้งองค์กร ซึ่งอาจมีอำนาจมากกว่าการเป็น CEO ของ unit เดียว
**โปรแกรมเมอร์มืออาชีพ:** ในทางปฏิบัติ ควรเริ่มติดตาม Kavukcuoglu แทน Hassabis สำหรับ Gemini API technical roadmap; Jeff Dean's departure ลบ institutional memory สำคัญออกจาก Google Research — ควรจับตาว่า research priorities จะ shift อย่างไรในไตรมาสถัดไป

## 2. Anthropic ประกาศสร้างทีมออกแบบชิป AI ของตัวเอง

**อาจารย์ (มหาวิทยาลัย):** นี่คือตัวอย่างของ vertical integration strategy ในยุค AI — เหมือน Apple ที่ควบคุม silicon เพื่อ competitive advantage ที่คู่แข่งไม่สามารถ replicate ได้ง่ายๆ ผ่าน software อย่างเดียว; ควรใช้เป็น case study เรื่อง make-vs-buy decision ใน technology strategy
**ผู้เชี่ยวชาญด้าน AI:** จุดสำคัญคือ "co-design" ระหว่างชิปและโมเดลพร้อมกัน ซึ่งต่างจากการ optimize โมเดลให้รันบน off-the-shelf GPU — ถ้าทำได้จริง efficiency gain จะมากกว่า software optimization อย่างมีนัยสำคัญ; Samsung partnership จะเป็นตัวกำหนดว่า timeline ความพร้อมจะเป็นอย่างไร
**โปรแกรมเมอร์มืออาชีพ:** ผลที่คาดได้ในระยะกลาง (2–3 ปี) คือ inference cost ของ Claude ที่ถูกลงและ latency ที่น้อยลง ซึ่งดีสำหรับ high-volume use cases; ระหว่างนี้ Anthropic ยังคงใช้ AWS, Google, NVIDIA และ AMD ควบคู่กัน ไม่มี disruption ต่อ Claude API ในระยะสั้น

## 3. White House ยกเว้น Chinese Open-Weight AI จากกรอบทดสอบความปลอดภัยของสหรัฐฯ

**อาจารย์ (มหาวิทยาลัย):** การตัดสินใจนี้สะท้อนความตึงเครียดระหว่าง innovation policy และ national security — การยกเว้น open-weight models สร้าง regulatory blind spot ที่สำคัญและอาจส่งผลระยะยาวต่อ AI governance framework ทั่วโลก ควรเป็น case study เรื่อง regulatory trade-offs
**ผู้เชี่ยวชาญด้าน AI:** ปัญหาหลักคือ open-weight models สามารถ fine-tune ได้ต่างกันมากขึ้นอยู่กับเจตนา — safety evaluation ควรดูที่ capability ceiling ไม่ใช่แค่ base weights; นโยบายนี้ทำให้รัฐบาลขาดข้อมูลสำคัญในการ track ว่า Chinese AI capabilities อยู่ที่ระดับไหนจริงๆ เมื่อ Z.ai's GLM-5.2 อยู่ห่างจาก frontier US models เพียงไม่กี่เดือน
**โปรแกรมเมอร์มืออาชีพ:** ในทางปฏิบัติ นโยบายนี้หมายความว่า Chinese open-weight models (GLM, Qwen, DeepSeek ฯลฯ) ยังคงเป็น option ที่ถูกกฎหมายสำหรับ commercial use ในสหรัฐฯ โดยไม่มี compliance barrier เพิ่มเติม — ยังคุ้มค่าที่จะ benchmark cost/performance ต่อไป

## 4. Yann LeCun ร่วมก่อตั้ง 224 Ventures กองทุน AI ระยะเริ่มต้นมูลค่า $100M+

**อาจารย์ (มหาวิทยาลัย):** การที่นักวิจัยระดับ frontier เปลี่ยน role มาเป็น capital allocator คือสัญญาณที่น่าสนใจ — พวกเขามักเห็น research gap ที่ market ยังไม่ address และใช้เงินเพื่อ fund research direction ที่พวกเขาเชื่อ; ควรวิเคราะห์ว่า "godfather" ของ deep learning เชื่อในทิศทางไหน
**ผู้เชี่ยวชาญด้าน AI:** LeCun ยังคงยืนยัน "world model" architecture เป็นทางไปข้างหน้า ต่างจากกระแสหลัก LLM — ดังนั้นบริษัทที่ 224 Ventures เลือกจะสะท้อน thesis นั้น และเป็น signal ที่ดีสำหรับ embodied AI, robotics และ foundation models ที่ไม่ใช่ transformer-only
**โปรแกรมเมอร์มืออาชีพ:** สำหรับ startup founders ใน early-stage AI — การมี LeCun และ Vinyals (Gemini co-lead) ใน cap table เป็น credibility signal ที่แข็งแกร่งมากสำหรับ downstream fundraising; จับตาบริษัทแรกที่ 224 Ventures เปิดเผยใน portfolio

## 5. Shopify: AI Search ช่วยขยายตลาด ไม่ใช่กิน Google

**อาจารย์ (มหาวิทยาลัย):** ข้อมูล Q2 ของ Shopify เป็นหลักฐานเชิงประจักษ์ที่พิสูจน์ "complement vs. substitute" theory ของ platform markets — ควรใช้เป็น data point ในการสอนเรื่อง market expansion เทียบกับ market substitution ในยุค AI
**ผู้เชี่ยวชาญด้าน AI:** ตัวเลข "75% นอก top 100 categories" เป็น signal สำคัญว่า AI search unlock latent demand — products ที่ keyword-based search ค้นหาได้ยาก แต่ conversational AI เข้าใจ intent ได้; นี่คือ fundamental advantage ที่ยาก replicate ด้วย SEO แบบเดิม
**โปรแกรมเมอร์มืออาชีพ:** ลงทุนใน AI discoverability ตอนนี้: structured data (schema.org), llms.txt, conversational product descriptions ที่ตอบ intent แทน keyword — ก่อนที่จะกลายเป็น commodity เหมือน SEO ในทศวรรษที่แล้ว; new buyer rate ที่ 2x จาก AI channels คือ business case ที่ชัดเจน
