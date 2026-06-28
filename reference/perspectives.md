# Perspectives — 2026-06-28

## 1. ออสเตรียล็อบบี้ EU ให้ "Host" Anthropic หนีบ US Export Ban

**อาจารย์ (มหาวิทยาลัย):** ประกาศของออสเตรียเป็น textbook case ของ "digital sovereignty" — EU กำลังเรียนรู้ว่า dependency บน AI ที่พัฒนาและควบคุมโดย single country คือช่องโหว่ทางกลยุทธ์ที่หลีกเลี่ยงไม่ได้ นักศึกษาควรศึกษาเปรียบเทียบกับ GDPR และ EU AI Act ว่า hosting infrastructure ต่างจาก regulatory control อย่างไร
**ผู้เชี่ยวชาญด้าน AI:** "Host" Anthropic ใน EU ฟังดูดีแต่ทางเทคนิคซับซ้อน — server location ≠ legal jurisdiction ≠ model control Anthropic ยังอยู่ภายใต้ US export control ตราบเท่าที่เป็น US entity แม้ว่า compute จะอยู่ใน Vienna ทางออกที่จริงกว่าคือการ spin out EU legal entity แบบที่บางบริษัทใช้เพื่อ comply กับ China regulations
**โปรแกรมเมอร์มืออาชีพ:** ถ้า Anthropic EU entity เกิดขึ้นจริง developer ภายนอก US จะได้ API endpoints ที่ไม่อยู่ภายใต้ US export restrictions — นั่นคือ potential unblock สำหรับ workloads ที่ถูกตัดไปตั้งแต่ June 2026 ควรเตรียม monitoring สำหรับ announcement นี้และวาง migration path ไว้ล่วงหน้า

## 2. Google จำกัด Meta ใช้ Gemini เพราะ Compute ไม่พอ

**อาจารย์ (มหาวิทยาลัย):** นี่คือตัวอย่างจริงของ "compute scarcity" economics — แม้แต่บริษัทขนาด Meta ที่มีทรัพยากรมหาศาลยังถูก cap โดย Google เพราะ TPU/GPU capacity มีจำกัด เหมาะมากสำหรับสอน resource allocation และ priority management ในบริบท AI infrastructure
**ผู้เชี่ยวชาญด้าน AI:** Google กำลังเผชิญ internal vs. external capacity tension — Gemini training runs, Gemini in Search, Google Cloud enterprise commitments, และ external customers ทั้งหมดดึง compute pool เดียวกัน การที่ Meta ถูก cap บ่งบอกว่า internal demand กำลัง outprioritize external SLAs ซึ่งเป็น warning sign สำหรับ enterprise customers ทุกราย
**โปรแกรมเมอร์มืออาชีพ:** ออกแบบ fallback logic ตั้งแต่ตอนนี้ — ถ้า primary model ไม่ตอบสนอง ควร degrade ไปใช้ smaller/cheaper model แทน ไม่ใช่ let the request fail Gemini API users ควรอ่าน quota documentation อย่างละเอียดและอย่า assume burst capacity เสมอ

## 3. BIS Annual Report เตือน: "AI Bust" คือ Top-Tier Risk ต่อเศรษฐกิจโลก

**อาจารย์ (มหาวิทยาลัย):** BIS Annual Report คือ primary source tier-1 สำหรับ economic policy research — การที่ BIS ระบุ AI bust เป็น "pressure point" ในระดับเดียวกับ inflation และ fiscal stress เป็น signal สำคัญ นักศึกษาเศรษฐศาสตร์ควรอ่านฉบับเต็มและตั้งคำถามว่า AI investment มีลักษณะ bubble ของ dot-com era หรือไม่ และถ้าแตก จะ cascade ออกอย่างไร
**ผู้เชี่ยวชาญด้าน AI:** BIS ไม่ได้ predict AI crash — แต่ identify transmission mechanism ว่า AI bust จะ amplify ผ่าน off-balance-sheet debt ของ hyperscalers → credit markets → systemic shock ความเสี่ยงไม่ได้อยู่ที่ AI technology ล้มเหลว แต่ที่ financial structure รอบๆ มัน ซึ่ง leverage สูงกว่าที่ balance sheet แสดง
**โปรแกรมเมอร์มืออาชีพ:** ถ้า VC funding tightens เพราะ AI bust สิ่งที่กระทบ developer ก่อนคือ API pricing เพราะ hyperscalers จะต้อง justify margins มากขึ้น — review AI cost structure ของโปรเจกต์ตอนนี้ หา optimization opportunity ก่อนที่ pricing จะ spike

## 4. Firmus + Nvidia ประกาศ Data Center 360 MW ในบาตัม อินโดนีเซีย

**อาจารย์ (มหาวิทยาลัย):** Batam อยู่ใน Indonesia-Malaysia-Singapore Growth Triangle (IMS-GT) ซึ่งเป็น economic cooperation framework ตั้งแต่ยุค 1990s — การที่ AI data center ขนาดใหญ่เลือก Batam แสดงว่า "proximity to Singapore" กับ "Indonesia cost advantage" คือ combination ที่ตลาดต้องการ เป็น case study ที่ดีของ economic geography ยุค AI
**ผู้เชี่ยวชาญด้าน AI:** 360 MW Nvidia DSX AI Factory ไม่ใช่ generic data center — DSX คือ Nvidia's integrated AI stack ที่รวม DGX systems, InfiniBand networking, และ NIM software เป็น turnkey AI compute facility การมี facility นี้ใน ASEAN หมายความว่า AI training workloads ไม่จำเป็นต้อง route ผ่าน US/Europe เท่านั้น
**โปรแกรมเมอร์มืออาชีพ:** Watch for AWS, Google Cloud, Microsoft Azure ที่จะ announce zones ใน Indonesia ตามหลัง — hyperscalers มักตาม power/connectivity infrastructure ไม่ใช่นำก่อน ถ้า application ของคุณ serve ASEAN users ให้ monitor cloud region announcements ในช่วง Q3-Q4 2026 อย่างใกล้ชิด

## 5. AI Fever ดัน IPO ฮ่องกง H1 2026 สู่ $44 พันล้านดอลลาร์ สูงสุดในรอบ 5 ปี

**อาจารย์ (มหาวิทยาลัย):** $44 billion ใน H1 เดียวของ Hong Kong ท้าทาย narrative ว่า AI investment เป็น US-centric — Asian capital markets กำลัง participate อย่างจริงจัง เป็นโอกาสที่ดีที่จะ discuss "AI multipolar world" ว่าแตกต่างจาก semiconductor/software ecosystem ยุคก่อนอย่างไร
**ผู้เชี่ยวชาญด้าน AI:** สิ่งที่ investor ใน HK buy คือ primarily AI-adjacent infrastructure (power, networking, real estate, finance) ไม่ใช่ frontier model companies โดยตรง เพราะ frontier models ส่วนใหญ่อยู่ใน US/EU ที่ยัง private หรือมี export restrictions นี่คือ "AI premium" ที่ flows ไปใน asset class ที่ไม่ถูก restrict
**โปรแกรมเมอร์มืออาชีพ:** HK/APAC VC และ PE capital ที่ deploy ในปีนี้จะ look for returns ใน 3-5 ปี — หมายความว่า AI infrastructure bets ที่ทำวันนี้จะ shape โครงสร้างพื้นฐาน AI ใน APAC ในปี 2029-2031 startup ที่ build บน APAC infrastructure กำลัง benefit จาก tailwind นี้
