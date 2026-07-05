# Perspectives — 2026-07-05

## 1. Amazon ปิดรับลูกค้าใหม่ Mechanical Turk

**อาจารย์ (มหาวิทยาลัย):** Mechanical Turk ไม่ใช่แค่บริการ — มันคือโครงสร้างพื้นฐานของ ML research ช่วงทศวรรษ 2010-2020 การปิดตัวสะท้อนว่า automated labeling ถึงจุดที่เพียงพอสำหรับ commodity tasks แล้ว แต่สิ่งที่ต้องสอนนักศึกษาคือ ความแตกต่างระหว่าง "งานที่ auto-label ได้" กับ "งานที่ต้องการ human judgment จริง ๆ" ยังมีอยู่และสำคัญมากขึ้น
**ผู้เชี่ยวชาญด้าน AI:** สัญญาณที่น่าสนใจคือ Amazon เลือกใช้ SageMaker Ground Truth เป็นทางออก ซึ่งผสม automated labeling กับ human review ในลักษณะ active learning — ไม่ใช่การกำจัดมนุษย์ออกจากกระบวนการ แต่เปลี่ยน interface จาก open marketplace เป็น managed pipeline ที่ควบคุมคุณภาพได้ดีกว่า
**โปรแกรมเมอร์มืออาชีพ:** สำหรับทีมที่ยังใช้ Mechanical Turk API ใน data annotation workflow: เส้นตาย July 30 ไม่ใช่เวลาเยอะ ให้ audit dependencies ก่อน แล้วค่อยเปรียบเทียบ SageMaker Ground Truth, Scale AI, Labelbox, หรือ Prolific ตามลักษณะงานและงบประมาณ

## 2. AI ครองครึ่งแรกของปี 2026 — Unicorn ใหม่เกือบ 90 ราย

**อาจารย์ (มหาวิทยาลัย):** การที่ OpenAI และ Anthropic รับเม็ดเงิน VC ไป 43% ของอุตสาหกรรม AI ทั้งหมดคือ market concentration ในระดับที่น่าวิเคราะห์ผ่านเลนส์เศรษฐศาสตร์และนโยบาย — เมื่อ compute และ distribution อยู่กับผู้เล่นไม่กี่ราย นักศึกษาต้องเข้าใจว่า innovation landscape ที่เหลือถูก shape อย่างไร
**ผู้เชี่ยวชาญด้าน AI:** การที่ Promethus ระดมทุน $12B Series B สำหรับ AI engineering automation บ่งชี้ว่าตลาดกำลัง bet ว่า agentic systems สำหรับ software development เป็น category ที่จะใหญ่มาก แต่ risk ที่ต้องติดตามคือว่า valuation สะท้อน revenue จริงหรือยัง หรือยังอยู่ในโหมด "winner takes all" speculation
**โปรแกรมเมอร์มืออาชีพ:** ดู unicorn list นี้เป็นแผนที่ของ AI tool ecosystem ที่กำลัง mature — ถ้า startups เหล่านี้รอด จะมี tools ใหม่เข้ามาใน workflow ของคุณภายใน 2-3 ปี ถ้าไม่รอดจะมี consolidation ที่ส่งผล lock-in risk; ทดสอบ alternative ก่อน ecosystem settle
