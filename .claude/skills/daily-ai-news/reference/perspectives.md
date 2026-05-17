# Perspectives — 2026-05-17

## 1. arXiv will ban authors for a year if they let AI do all the work

**อาจารย์ (มหาวิทยาลัย):** นโยบายนี้สะท้อนวิกฤตความน่าเชื่อถือของงานวิชาการในยุค LLM — นักศึกษาต้องเข้าใจว่า arXiv เป็น infrastructure สำคัญของวิทยาศาสตร์โลก และการที่ LLM-generated papers ระบาดเป็นร้อยชิ้นต่อเดือนทำให้ peer reviewers มีภาระเพิ่มขึ้นจน signal-to-noise ratio ลดลงอย่างน่าเป็นห่วง ซึ่งกระทบคุณภาพวิทยาศาสตร์ระยะยาว
**ผู้เชี่ยวชาญด้าน AI:** น่าสนใจที่ arXiv เลือก "social enforcement" (ban + peer review requirement) แทน AI detection tools เพราะ detectors เหล่านั้นยัง false positive สูงและ adversarially fragile — อย่างไรก็ตาม นโยบายนี้สร้าง perverse incentive ให้ผู้เขียนซ่อน AI use แทนที่จะ disclose อย่างโปร่งใส ซึ่งอาจซับซ้อนกว่าปัญหาเดิม
**โปรแกรมเมอร์มืออาชีพ:** ถ้าคุณ publish งานวิจัยควบคู่กับ product ต้องปรับ workflow ให้มี audit trail ชัดเจนว่า human contributed อะไรบ้าง ตั้งแต่วันนี้ — journals และ conferences จะออก policies คล้ายกันในเร็ว ๆ นี้ และ LLM-assisted code documentation ก็อยู่ในสายตาเดียวกัน

## 2. $60B AI chip darling Cerebras almost died early on, burning $8M a month

**อาจารย์ (มหาวิทยาลัย):** Cerebras คือ case study ของ "technical moat through impossible bet" — บริษัทเลือกสร้าง Wafer-Scale Engine ซึ่ง risk ระดับ existential เผา $200M ก่อนจะรู้ว่าใช้ได้จริง นักศึกษา engineering และ entrepreneurship ควรวิเคราะห์ว่าทำไม investor จึงยังสนับสนุนต่อในช่วงที่ burn rate สูงและไม่มีหลักประกันของผลลัพธ์
**ผู้เชี่ยวชาญด้าน AI:** WSE3 ของ Cerebras โดดเด่นที่ inter-chip bandwidth ต่ำมาก ทำให้ latency ต่ำในงาน long-context single-request inference แต่ GPU cluster ยังชนะใน parallel batch workloads — ดังนั้น use case ที่เหมาะที่สุดคือ real-time interactive AI ที่ต้องการ response time ต่ำกว่า 100ms สำหรับ context ยาว
**โปรแกรมเมอร์มืออาชีพ:** Cerebras Cloud API พึ่งขยายหลัง IPO — ลอง benchmark กับ long-context inference workloads จริงของตัวเอง ถ้าต้องการ low-latency long-context responses (>32K tokens) อาจคุ้มค่ากว่า GPU providers ที่ใช้อยู่สำหรับ use cases เฉพาะเจาะจง

## 3. The haves and have nots of the AI gold rush

**อาจารย์ (มหาวิทยาลัย):** ปรากฏการณ์นี้ไม่ใช่แค่ wealth gap แต่คือ "knowledge and access gap" ในระดับที่ไม่เคยเกิดขึ้นในรอบการปฏิวัติเทคโนโลยีใดมาก่อน — คน 10,000 คนนั้นกำลัง shape trajectory ของ AI ขณะที่คนส่วนใหญ่ยังเป็น passive consumer ซึ่งมีนัยต่อ democratic governance of AI ที่ต้องพูดถึงในหลักสูตร AI ethics
**ผู้เชี่ยวชาญด้าน AI:** ตัวเลข 10,000 คน ($20M+) ชี้ว่า equity concentration เป็น winner-take-most ไม่ใช่ winner-take-all — ยังมี second-tier upside ที่ Mistral, Cohere, Runway แต่ gap กับ frontier labs กว้างขึ้นทุกเดือนเมื่อ valuation เพิ่มขึ้น exponentially ทำให้ early employees ใหม่ในบริษัทเหล่านี้ได้ upside น้อยลงเรื่อย ๆ
**โปรแกรมเมอร์มืออาชีพ:** อย่า discouraged เพราะไม่ได้อยู่ใน top 10K — demand สำหรับ AI integration engineering, agentic orchestration, RAG pipeline optimization, และ fine-tuning ยังโตต่อเนื่องในทุก sector และ skills เหล่านี้สร้าง leverage ที่แข็งแกร่งในตลาดแรงงานปัจจุบัน
