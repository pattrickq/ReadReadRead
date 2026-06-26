# ReadReadRead — Market Research & Product Concept

Source: Startup Exploration Doc (Google Docs, June 2026)
Status: Early ideation

> **Pat's note on market target:** Doc นี้ assume Global day 1 แต่ตอนนี้กำลังคิดอยู่ว่าควร **target ตลาดไทยก่อน** เพื่อ validate concept ก่อนที่จะ scale global — ข้อมูลตลาดไทยด้านล่างน่าจะ relevant มากสำหรับการตัดสินใจนี้

---

## 1. Market Overview

### Global E-Book Market
- มูลค่าตลาดปี 2025: ~$18–25 billion USD
- CAGR คาดการณ์ 4–6% ต่อปี ถึงปี 2030–2031
- North America ครอง ~39–44% ของ global share
- Asia Pacific เติบโตเร็วที่สุด — mobile reading engagement สูงกว่า Western markets ถึง 50%
- Subscription model ครอง 55% ของ revenue ปี 2025

### Thailand E-Book Market
- มูลค่าตลาด e-book ไทย: ~3 พันล้านบาท
- ตลาด e-reader ไทย: 140 ล้านบาท (2024) เติบโต 60% YoY
- User penetration ยังต่ำ ~7.3% (2024) คาดแตะ 8.5% ในปี 2027
- คาดมีผู้อ่าน e-book ในไทย 6 ล้านคนในปี 2027
- ตลาดหนังสือรวม 20 พันล้านบาทในปี 2025 ขับเคลื่อนด้วย digital + creative content
- Gen Z คือ driving force — 70% ของผู้เข้างาน Book Expo Thailand 2025
- PUBAT คาดโต 5–10% ในปี 2026 ขับเคลื่อนด้วย cross-media storytelling, e-book, audiobook

---

## 2. Competitive Landscape

### Incumbents (ใหญ่แต่เก่า)
| Platform | จุดแข็ง | จุดอ่อน |
|---|---|---|
| Goodreads | 150M users, community | UI ไม่เปลี่ยนตั้งแต่ Amazon ซื้อปี 2013, cluttered, neglected |
| Kindle | Reading experience ดี, ecosystem ใหญ่ | Discovery แย่, ขาด social layer |

### Challengers (กำลังโต)
| Platform | โฟกัส | Users | จุดอ่อน |
|---|---|---|---|
| StoryGraph | Stats, mood, pace-based recommendation | ~4M | อ่อนด้าน social, web-first |
| Fable | Social reading, book clubs (ถูก Scribd ซื้อปี 2025) | 1M+, 100K+ clubs | อ่อนด้าน personal tracking stats |
| Hardcover | Community-curated lists, ex-Goodreads engineers | เล็ก | Catalog gap, mobile lagging |
| Bookly | Reading timer, streaks, gamification | - | ไม่มี social, ไม่มี discovery |

### Where Discovery Actually Happens (2026)
- TikTok / Instagram คือ channel หลัก — 1 ใน 4 user search ใน app ภายใน 30 วินาทีแรก
- Reader ค้นพบหนังสือบน social media แต่ต้องไปซื้อและอ่านที่อื่น — ไม่มีใคร close the loop ในที่เดียว

### Gaps ที่ยังไม่มีใครแก้
- ไม่มี platform ที่ทำ social + discovery + reading ได้ดีในที่เดียว
- ทุก app gamify แค่ streak + badge — ยังไม่มีใคร gamify ตัว reading experience จริงๆ
- Discovery ยังแยกออกจาก reading experience

---

## 3. Product Concept

**Angle:** Reader experience app ที่เน้น gamified collectible layer ผูกกับ reading progression

### Core Mechanic: Character Unlock by Read Progression
- ฟีล Steam achievement บน reading platform
- อ่านถึง chapter ที่กำหนด → unlock character จากเรื่องนั้น ในรูป collectible artwork
- Character ที่ยังไม่ถึงแสดงเป็น silhouette (สร้าง curiosity โดยไม่ spoil)
- Artwork มาจาก artist collaboration — value ที่ tangible และ ownable
- Collection page แสดง visual reading history

### ทำไม Mechanic นี้ Work
- ไม่ force user ทำอะไรเพิ่ม — แค่อ่านก็ unlock
- Character locked กลายเป็น pull ให้อ่านต่อ แทนที่จะเป็นภาระ
- เป็น proof ว่า "อ่านจริง" โดยไม่ต้อง write review
- Artist collaboration ดึง collector community เพิ่มเติม

### Mechanics อื่นที่เก็บไว้ (ไม่ใช่ priority แรก)
- Streak-based character evolution
- Genre DNA — character reflect reading personality
- Social flex — collection page บน profile
- Cross-title collection

> หมายเหตุ: Quiz mechanic ไม่ใช่ priority — รู้สึกเป็นภาระ user

---

## 4. Content Strategy

### Public Domain เป็น Starting Catalog
- Project Gutenberg มี ~78,000 titles (มีนาคม 2026) เพิ่มใหม่ 30+ เล่ม/สัปดาห์
- Standard Ebooks นำ Gutenberg มา reformat ให้ professional typography
- Content cost = $0

### Public Domain Titles ที่ยังมี Pull
| กลุ่ม | ตัวอย่าง |
|---|---|
| Dark academia / gothic | Frankenstein, Dr Jekyll & Mr Hyde, Dorian Gray, Dracula |
| Mystery / thriller | Sherlock Holmes, The Count of Monte Cristo |
| Romance / emotional | Jane Eyre, Pride and Prejudice, Wuthering Heights |
| Philosophy / self-help | Meditations (Marcus Aurelius), Walden |

### ข้อจำกัดของ Public Domain
- BookTok viral content ส่วนใหญ่ยังมี copyright (Fourth Wing, ACOTAR ฯลฯ)
- Reader หน้าใหม่จาก TikTok มักอยากอ่าน contemporary fiction ไม่ใช่ classics
- Public domain เหมาะกับคนอยากอ่านแต่ไม่รู้จะเริ่มที่ไหน มากกว่า trend follower

---

## 5. Business Model

| Revenue Stream | Detail |
|---|---|
| Freemium subscription | อ่านฟรี (public domain) + unlock character ฟรี / Premium = copyrighted titles + variant artwork |
| Variant artwork | Character เดิม artist คนละคน หรือ seasonal art เป็น premium unlock |
| Complete set bonus | อ่านครบทุก character ใน title unlock bonus artwork หรือ epilogue |

### Target Unit Economics
- Target $1M ARR ปีแรก
- Subscription $8/mo = ต้องการ ~10,400 paying users
- Freemium conversion 3–5% = ต้องการ user base 200,000–350,000 คน

### Risks หลัก
| Risk | รายละเอียด |
|---|---|
| Content cost ก่อนมีรายได้ | 20 titles x 10 characters x $200/artwork = $40,000 แค่ initial art asset |
| Cold start ของ collection | Catalog น้อย → collection หน้าว่าง → ไม่มี pull |
| แข่งกับฟรี | Public domain อ่านได้ฟรีที่อื่น — value ต้องมาจาก experience + collectible |
| Willingness to pay | Digital collectible ใน reading context ยังไม่ proven |

---

## 6. Open Questions

- มี unfair advantage อะไรในการ acquire artist หรือ content ที่คนอื่นทำได้ยาก?
- Target user คือคนที่ชอบอ่านอยู่แล้ว หรือคนที่อยากอ่านแต่ยังไม่ทำ? (สองกลุ่มต้องการ product ต่างกัน)
- จะ acquire user 200k+ คนด้วยอะไรถ้าไม่มี paid marketing budget?
- Character design: collect หลายตัว หรือ evolve ตัวเดียว?
- User เห็น character แค่ใน profile หรือ character มี role ระหว่างอ่านด้วย?
- Aesthetic direction: pixel art, illustration, anime-style หรืออื่น?

---

## 7. Recommended Next Steps

- **MVP scope** — เริ่มจาก public domain 2–3 titles + artist คนเดียว ทดสอบว่า user engage กับ character collection จริงไหม
- **Go-to-market** — ยังไม่ได้ explore ควรคุยต่อ
- **Artist pipeline** — ต้องมี process ที่ scale ได้ก่อน commit กับ publisher หรือ content creator

---

## Pat's Strategic Note

Doc นี้ assume **Global day 1** แต่มีความกังวลว่าควร **target ตลาดไทยก่อน** เพราะ:
- ตัวเลขตลาดไทยโตเร็ว (60% YoY), Gen Z เป็น driving force
- Validate concept ในตลาดที่เข้าใจก่อนจะ scale global ทำได้ง่ายกว่า
- User penetration ยังต่ำ (7.3%) = ยังมีที่ว่างให้เข้าไป
- ถ้า product-market fit ดีในไทย → scale เป็น SEA → global ต่อได้

คำถามที่ต้องตัดสินใจ: Thailand first หรือ Global day 1?
