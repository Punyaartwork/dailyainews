# Perspectives — 2026-05-20

## 1. Gemini 3.5 Flash — Google bets its next AI wave on agents, not chatbots

**อาจารย์ (มหาวิทยาลัย):** นักศึกษาต้องเข้าใจว่า "agentic AI" ไม่ใช่แค่ชื่อใหม่ของ automation — มันคือ software paradigm ใหม่ที่ AI วางแผน ตัดสินใจ และ iterate โดยไม่ต้องมีคนนำทางทุกขั้นตอน Gemini 3.5 Flash ที่สามารถ "build an OS from scratch" ในการทดสอบคือ concrete example ที่ควรนำเข้า curriculum
**ผู้เชี่ยวชาญด้าน AI:** การที่ Flash 3.5 beat Pro 3.1 บน agentic benchmarks บอกว่า Google optimize ขนาด/ต้นทุนสำหรับ deployment จริง ไม่ใช่แค่ research — เป็นสัญญาณว่า performance frontier กำลัง commoditize เร็วกว่าที่ตลาดคาด ต้องดูว่า model นี้ทำงานอย่างไรบน real-world tasks ที่มี noisy environment
**โปรแกรมเมอร์มืออาชีพ:** Gemini 3.5 Flash เป็น default ใน Gemini Enterprise แล้ว หมายความว่า agentic pipeline ที่ build บน Gemini API ตอนนี้จะใช้ model นี้โดยอัตโนมัติ ลอง test ว่า tool use และ multi-step reasoning ดีขึ้นใน production จริงหรือเปล่าก่อน commit architecture

## 2. Google Search as you know it is over

**อาจารย์ (มหาวิทยาลัย):** Generative UI ใน Search คือ moment ที่ต้องสอนนักศึกษาให้ตั้งคำถามว่า "ใครสร้าง content" เมื่อ AI generate visualization ตอบคำถาม — source attribution และ academic integrity ใน AI era ต้องถูก redefine ในทุก discipline
**ผู้เชี่ยวชาญด้าน AI:** การสร้าง generative UI แบบ real-time ที่ ground บน live data โดยรักษา factual consistency ข้าม follow-up queries คือ engineering challenge ยากกว่า text generation มาก ต้องดูว่า Google จะจัดการ hallucination ใน visual context อย่างไร
**โปรแกรมเมอร์มืออาชีพ:** SEO ที่รู้จักกันหมดสิ้นแล้ว — traffic model ใหม่คือ "ข้อมูลของคุณปรากฏใน information agents ได้หรือเปล่า" ให้ invest ใน structured data, APIs และ data quality มากกว่า keyword optimization

## 3. Google introduces Gemini Spark

**อาจารย์ (มหาวิทยาลัย):** Gemini Spark ที่รับคำสั่งผ่าน Gmail คือ example ที่ดีของ "interface for human-agent collaboration" — ชวนนักศึกษาคิดว่า workflow ของงานแต่ละประเภทจะ delegate ส่วนไหนให้ agent ได้และส่วนไหนควรมีมนุษย์ดูแล
**ผู้เชี่ยวชาญด้าน AI:** Cloud-based agent ที่ทำงาน background ขณะผู้ใช้ไม่ online มี security และ privacy implication ที่ต้องพิจารณาอย่างจริงจัง โดยเฉพาะการที่ Spark สามารถ read emails, docs, และ browse เว็บ — trust boundary ของ agentic system ยังไม่มี industry standard ที่ชัดเจน
**โปรแกรมเมอร์มืออาชีพ:** MCP integration ของ Spark เปิดโอกาสให้ tools ของคุณ "เป็น API ที่ Spark ใช้" — ลงทุน expose API ผ่าน MCP schema ตั้งแต่ตอนนี้เพื่อรองรับ agent ecosystem ที่กำลังเติบโต

## 4. Google's Gemini Omni

**อาจารย์ (มหาวิทยาลัย):** Video generation ที่มี historical/cultural reasoning ระดับนี้เปลี่ยน dynamic ของ educational content production — ให้นักศึกษาคิดว่า AI-generated explainer video กับ video ที่มนุษย์ผลิตต่างกันใน context อะไรบ้าง และ trust ควรให้น้ำหนักต่างกันอย่างไร
**ผู้เชี่ยวชาญด้าน AI:** Native multimodal model ที่ reason ข้าม modalities แทน pipeline ต่อกัน คือ architectural leap ที่ลด error accumulation และ latency — เป็นสิ่งที่ research community พูดถึงมาหลายปี ต้องดูว่า consistency ข้าม modalities จะ hold ใน complex prompt จริงหรือเปล่า
**โปรแกรมเมอร์มืออาชีพ:** Google Flow API สำหรับ Gemini Omni น่าจะมี favorable pricing เพราะ Google optimize สำหรับ YouTube Shorts volume — ทำให้เป็นตัวเลือกที่น่าสนใจสำหรับ consumer app ที่ต้องการ video generation ต้นทุนต่ำ

## 5. OpenAI + Google image provenance (C2PA + SynthID)

**อาจารย์ (มหาวิทยาลัย):** C2PA + SynthID คือโอกาสสอนนักศึกษาเรื่อง trust chain ใน digital media — ให้นักศึกษาทดสอบ public verification tool ของ OpenAI กับรูปที่ AI-generate เพื่อเข้าใจว่า provenance system ทำงานอย่างไรและมีจุดอ่อนที่ไหน
**ผู้เชี่ยวชาญด้าน AI:** การที่ OpenAI และ Google ร่วมมือกันบน content provenance ทั้งที่แข่งกันดุเดือดในด้านอื่นสะท้อนว่า trust infrastructure ถูกมองเป็น public good — แต่ยังต้องการ platform adoption (browsers, social media, OS) เพื่อให้มีผลจริงในระดับ systemic
**โปรแกรมเมอร์มืออาชีพ:** C2PA กำลัง converge กลายเป็น industry standard จริง ให้ implement metadata tagging ใน image generation endpoint ของ product ตั้งแต่ตอนนี้ — ต้นทุนต่ำมาก แต่ผลระยะยาวคือ compliance ready สำหรับ platform requirements ที่กำลังมา
