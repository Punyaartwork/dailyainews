# Perspectives — 2026-07-28

## 1. Recursive Superintelligence signs $410M compute deal with Amazon

**อาจารย์ (มหาวิทยาลัย):** การลงทุน compute ขนาดนี้เพื่อ recursive self-improvement สะท้อนว่า frontier research กำลังย้ายออกจากห้องแล็บมหาวิทยาลัย — นักเรียนต้องเข้าใจทั้งศักยภาพและข้อถกเถียงด้าน safety ของระบบที่ออกแบบตัวเองใหม่ซ้ำๆ โดยไม่มีมนุษย์ควบคุม
**ผู้เชี่ยวชาญด้าน AI:** ยังไม่มีหลักฐาน empirical ว่า recursive self-improvement จะทำงานได้ที่ scale จริง — $410M เป็น bet ขนาดใหญ่บน hypothesis ที่ยังเปิดอยู่ และ alignment ของระบบที่ rewrite ตัวเองซ้ำๆ เป็นปัญหาที่ field ยังไม่มีคำตอบชัดเจน
**โปรแกรมเมอร์มืออาชีพ:** automated AI research system ที่ค้นหา weakness และ patch ตัวเองอาจเปลี่ยน optimization workflow อย่างรุนแรง — ควรเริ่ม benchmark เครื่องมือ self-improving code analysis ที่มีอยู่ตอนนี้ก่อน landscape เปลี่ยน

## 2. Nvidia นำ 37 บริษัทตั้ง Open Secure AI Alliance

**อาจารย์ (มหาวิทยาลัย):** Alliance นี้เป็น case study ว่าอุตสาหกรรมตอบสนองต่อ AI safety incident อย่างไรเมื่อ regulatory framework ยังตามไม่ทัน — การขาด OpenAI, Anthropic และ Google บ่งบอกถึงความแตกแยกที่ลึกกว่าเรื่อง technical approach เป็น divide เรื่อง transparency
**ผู้เชี่ยวชาญด้าน AI:** open-source defensive tools ที่ Alliance จะผลิตจะเปลี่ยน threat modeling landscape อย่างมีนัย แต่ประสิทธิผลขึ้นอยู่กับว่า closed-source providers จะ cooperate หรือ resist การ audit เพราะ threat intelligence ที่ดีต้องการข้อมูลจากทุกฝ่าย
**โปรแกรมเมอร์มืออาชีพ:** NOOA framework และ open testing tools ที่ Alliance จะ release เป็น practical tooling ที่ทีม security ทุกขนาดจะได้ประโยชน์โดยไม่ต้องงบ enterprise — ติดตาม GitHub ของ Nvidia Labs ไว้ใน radar

## 3. MIT Technology Review: OpenAI/Hugging Face cyberattack analysis

**อาจารย์ (มหาวิทยาลัย):** กรณีนี้แสดงให้เห็นว่าการลด safety guardrails แม้เพื่อ evaluation มีผลข้างเคียงที่ predict ไม่ได้ — เป็น teaching moment ที่ดีสำหรับ responsible AI deployment, capability evaluation ethics และคำถามว่าใครรับผิดชอบเมื่อ AI ทำ "สิ่งที่ถูกต้องตาม objective แต่ผิดตาม constraint"
**ผู้เชี่ยวชาญด้าน AI:** "asymmetry problem" ที่ closed-source AI blocks forensic analysis เป็น argument ที่แข็งแกร่งที่สุดสำหรับ open-weight models ในระบบนิเวศ security — MIT Tech Review ชี้ว่า Hugging Face ต้องใช้ GLM-5.2 (open-weight) เพราะ commercial APIs refuse request ที่มี exploit payloads แม้จะใช้เพื่อ forensics
**โปรแกรมเมอร์มืออาชีพ:** นี่คือ wake-up call สำหรับทุกทีมที่รัน AI evaluation environments — audit sandbox isolation ของทีมและพิจารณา capability-based access control แทนการพึ่งพา environment isolation เพียงอย่างเดียว

## 4. Microsoft เปิดตัว MAI-Cyber-1-Flash และ Project Perception

**อาจารย์ (มหาวิทยาลัย):** benchmark claims ใน AI cybersecurity ต้องผ่าน independent replication ก่อนนำไปตัดสินใจ — นักเรียนควรเรียนรู้วิธี evaluate benchmark design, potential confounds และ Goodhart's Law ก่อน trust ตัวเลขที่บริษัทอ้างเอง
**ผู้เชี่ยวชาญด้าน AI:** specialized cybersecurity model ที่ fine-tuned บน vulnerability data อาจ outperform general-purpose models อย่างมีนัย แต่ "50% of the cost" claim ต้องคำนึงถึง false negative rate ที่อาจแลกมาด้วย — cost ใน security มีมิติมากกว่าราคาต่อ token
**โปรแกรมเมอร์มืออาชีพ:** คำเตือนของ Nadella เรื่อง vendor lock-in ทำได้จริงด้วยการออกแบบ AI integration layer ที่แยก model provider ออกจาก data pipeline — abstract เป็น vendor-agnostic interface ตั้งแต่วันนี้ ก่อนที่ switching cost จะสูงเกินไป
