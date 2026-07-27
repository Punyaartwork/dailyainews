# Perspectives — 2026-07-27

## 1. Kimi K3 open weights ออกแล้ว: 2.8 ล้านล้านพารามิเตอร์

**อาจารย์ (มหาวิทยาลัย):** การปล่อย Kimi K3 ในฐานะ open-weight model เป็น turning point สำหรับ AI education — ห้องแล็บมหาวิทยาลัยที่ไม่มีงบประมาณ API ราคาสูงสามารถ fine-tune frontier-class model บน domain-specific data ได้เองแล้ว และ MXFP4 quantization, MoE sharding ขนาดใหญ่ต้องเป็น skills พื้นฐานที่นักศึกษา ML ยุคถัดไปต้องเข้าใจ
**ผู้เชี่ยวชาญด้าน AI:** Kimi K3 ลดช่องว่างระหว่าง open และ closed models จนถึงจุดที่ enterprise ต้องประเมิน total cost of ownership ใหม่ทั้งหมด — latency, privacy, control และ vendor lock-in vs API convenience; ประเด็น geopolitical เรื่อง distillation และชิปต้องห้ามยังเป็น unsettled question ที่อาจนำไปสู่ regulation ของ open-weight releases
**โปรแกรมเมอร์มืออาชีพ:** day-0 hosted access บน Together AI และ Modal ให้ benchmark Kimi K3 ต่อ workload จริงได้วันนี้เลย; ถ้าต้อง self-host ต้องเตรียม 1.4 TB storage, multi-GPU setup และเข้าใจ MXFP4 precision limits ให้ดีก่อนลงทุน infrastructure

## 2. Nvidia เจรจาค้ำประกัน $250B ให้ OpenAI เช่า data center ของ SoftBank

**อาจารย์ (มหาวิทยาลัย):** Deal นี้ควรอยู่ใน syllabus วิชา technology policy — compute infrastructure กำลังกลายเป็น critical resource ในแบบเดียวกับพลังงานและ semiconductor นำมาสู่คำถามเรื่อง antitrust, national security และ concentration of power ที่ต้องวิเคราะห์ในเชิง public policy
**ผู้เชี่ยวชาญด้าน AI:** 10-gigawatt campus จะเปลี่ยน cost curve ของ frontier training อย่างมีนัยสำคัญ แต่ก็สร้าง single point of failure ระดับชาติ; การที่ Google, Anthropic และ Microsoft ก็สนใจ campus นี้บ่งชี้ว่านี่คือ land grab บน next-generation compute อย่างแท้จริง
**โปรแกรมเมอร์มืออาชีพ:** Nvidia ในฐานะ financier และ guarantor ของ AI infrastructure จะเพิ่ม pricing leverage ต่อ cloud API ในระยะกลาง — ถึงเวลาออกแบบ system ให้ model-agnostic และ benchmark ราคา inference ข้าม provider อย่างสม่ำเสมอแทนที่จะผูกกับ vendor เดียว

## 3. Google AI Overviews ขึ้นเป็น 43% ของการค้นหา

**อาจารย์ (มหาวิทยาลัย):** ตัวเลข 43% หมายความว่านักเรียนส่วนใหญ่ไม่ได้เห็น "10 blue links" อีกต่อไปแต่รับ synthesized answer ก่อน — information literacy สมัยใหม่ต้องสอนให้รู้จักโต้แย้ง ขอแหล่งอ้างอิง และ sanity-check AI Overviews กับแหล่งข้อมูลหลัก
**ผู้เชี่ยวชาญด้าน AI:** 43% นี้อาจเป็น undercount เพราะ Google ยังปรับ ranking ใน 57% ที่ไม่ปรากฏ Overview ผ่าน AI ด้วย — ความเป็นจริงคือ AI ควบคุม information flow ของ search มากกว่าตัวเลขนี้บ่งชี้ และยังไม่มี external audit mechanism ที่แท้จริง
**โปรแกรมเมอร์มืออาชีพ:** SEO model เดิมที่ optimise บน "keywords → clicks → page" กำลังพัง — content ที่ AI เลือก cite มักมี structured data, clear factual claims และ authoritative sourcing ที่ชัดเจน ถึงเวลาลงทุนใน schema markup, fact density และ E-E-A-T signals แทน traditional link-building

## 4. Apple ทดสอบต้นแบบแว่นตา AI เน้นความเป็นส่วนตัว

**อาจารย์ (มหาวิทยาลัย):** Apple Smart Glasses เป็น textbook case ของ "privacy-by-design" ที่ควรนำมาสอนใน tech ethics — constraint ด้านความเป็นส่วนตัวถูก embed ตั้งแต่ hardware layer (on-device only, no recording) แทนที่จะเป็นแค่ software policy overlay ซึ่งเป็นความแตกต่างเชิงพื้นฐาน
**ผู้เชี่ยวชาญด้าน AI:** On-device visual AI ที่ Apple พัฒนาจะ push edge computing capabilities ในแบบที่ cloud-dependent solutions ทำไม่ได้ — latency ต่ำกว่า, privacy สูงกว่า แต่ model size จะถูก constraint อย่างหนักจาก thermal และ battery budget; ดูว่า Apple จะ handle model updates อย่างไรเมื่อ on-device storage จำกัด
**โปรแกรมเมอร์มืออาชีพ:** ถ้า Apple เปิด Vision AI API บน smart glasses, CoreML stack ปัจจุบันน่าจะเป็น foundation ที่ใช้ต่อได้ — เตรียม on-device ML pipeline และเข้าใจ low-power inference constraints ตั้งแต่ตอนนี้เพื่อ advantage ในตลาด spatial computing
