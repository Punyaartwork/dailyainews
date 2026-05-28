# Perspectives — 2026-05-28

## 1. ByteDance Weighs Capex of as Much as $70 Billion in AI Push

**อาจารย์ (มหาวิทยาลัย):** การที่บริษัทเดียววางงบลงทุน AI สูงกว่า GDP ของหลายประเทศชี้ให้นักศึกษาเห็นว่า compute infrastructure คือ "ทุนทางกายภาพ" ยุคใหม่ — ควรศึกษาเศรษฐศาสตร์การลงทุนในโครงสร้างพื้นฐานดิจิทัลควบคู่กับ AI techniques เพื่อเข้าใจว่าใครจะได้เปรียบในระยะยาว
**ผู้เชี่ยวชาญด้าน AI:** $70B จาก organic profit ไม่ใช่จากการ dilute equity — ByteDance มี flywheel ที่ sustainable กว่า pure-play AI labs แต่ความท้าทายใหญ่คือ chip export controls ที่บังคับให้พึ่ง domestic alternatives ซึ่งยัง performance gap กับ NVIDIA H100 อยู่มาก
**โปรแกรมเมอร์มืออาชีพ:** Doubao ecosystem กำลัง scale อย่างรวดเร็ว — developers ที่ต้องการ diversify จาก OpenAI/Anthropic single-vendor dependency ควรเริ่มศึกษา ByteDance AI APIs โดยเฉพาะถ้า target ผู้ใช้ในตลาดจีน

## 2. Tech CEOs are apparently suffering from AI psychosis

**อาจารย์ (มหาวิทยาลัย):** นี่คือตัวอย่างคลาสสิกของ cognitive bias จาก information asymmetry — CEO ที่ห่างจาก execution เห็นเฉพาะ "happy path" ของ demo แต่ไม่เห็น edge cases ที่ทีม technical ต้องจัดการ เป็น case study ที่ดีมากสำหรับวิชา organizational behavior
**ผู้เชี่ยวชาญด้าน AI:** Levie พูดถูก — gap ระหว่าง "demo quality" กับ "production quality" ยังกว้างมาก enterprise AI มี failure modes จำนวนมากที่ไม่ปรากฏใน controlled demo เช่น hallucinated API calls, data leakage และ behavior drift เมื่อ input นอก distribution
**โปรแกรมเมอร์มืออาชีพ:** Engineers คือผู้รับผิดชอบ "last mile" ที่ CEO ไม่เห็น — ควรสร้าง AI acceptance testing suite ที่ครอบคลุม edge cases จริงและ document failure cases ให้ leadership เห็น ก่อนที่จะถูก pressure ให้ ship เร็วเกินไป

## 3. Why Google's AI can't spell Google (or anything else)

**อาจารย์ (มหาวิทยาลัย):** กรณีนี้เป็นโอกาสทองสอนว่า LLM ไม่ได้ "รู้" ภาษาแบบที่มนุษย์รู้ — การ tokenize text เป็น numerical vectors หมายความว่า AI ไม่มี concept ของ "ตัวอักษร" ในแบบที่เราเข้าใจ ควรนำไปสอนใน computational linguistics และ AI literacy ทุกหลักสูตร
**ผู้เชี่ยวชาญด้าน AI:** spelling อาจดูเป็นเรื่องตลก แต่เป็น symptom ของ fundamental architectural limitation — transformer tokenizers ถูกออกแบบสำหรับ semantic understanding ไม่ใช่ character-level processing ซึ่งกระทบ use cases จริงอย่าง OCR post-correction, exact brand name matching และ structured data extraction
**โปรแกรมเมอร์มืออาชีพ:** ถ้า pipeline ต้องการ character-level precision ไม่ควรพึ่ง LLM โดยตรง — ใช้ regex, exact-match lookup หรือ rule-based post-processing layer แทน และเพิ่ม spelling validation ของ proper nouns เป็น standard acceptance criteria ใน AI feature ทุกอัน

## 4. China is increasingly keeping its best AI talent to itself

**อาจารย์ (มหาวิทยาลัย):** กรณี Manus-Meta เปิดมิติใหม่ให้นักศึกษา law และ business ต้องศึกษา — foreign investment review กลายเป็น strategic tool ที่รัฐบาลใช้ควบคุม technology transfer ในยุค geopolitics AI ซึ่งซับซ้อนกว่าการเจรจาการค้าธรรมดามาก
**ผู้เชี่ยวชาญด้าน AI:** ตัวเลข Stanford 2.7% gap บ่งชี้ว่า Chinese labs สามารถ replicate architectural innovation โดยไม่ต้องพึ่ง foreign hardware มากแล้ว — chip export controls ชะลอได้แต่ไม่หยุดได้ในระยะยาว
**โปรแกรมเมอร์มืออาชีพ:** ผลกระทบต่อ open-source ecosystem ที่น่ากังวลคือการ fragment ของ global knowledge sharing — ควรเริ่ม snapshot และ mirror contributions สำคัญจาก Chinese research teams ก่อนที่ collaboration จะถูกจำกัดมากขึ้น
