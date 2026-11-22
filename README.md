# 🚀 Planetary Survivors

เกมแนว **2D Survival Roguelike** สไตล์ Retro Sci-Fi เอาชีวิตรอดจากฝูงเอเลี่ยนบนดาวเคราะห์ต่าง ๆ พัฒนาด้วย **HTML5 Canvas** และสร้างระบบเสียงประกอบแบบสังเคราะห์สดด้วย **Web Audio API** รองรับการเล่นทั้งบนคอมพิวเตอร์และหน้าจอสัมผัสมือถือ

🎮 **ทดลองเล่นเกมออนไลน์ (Live Demo):** [https://nueame.github.io/planetary-survivors/](https://nueame.github.io/planetary-survivors/)

---

## ✨ ฟีเจอร์หลักของเกม (Key Features)

* **ตัวละคร 3 สายอาชีพ (3 Playable Survivors):** เลือกเล่นได้ทั้ง **Fisherman**, **Hunter** และ **Engineer** ซึ่งแต่ละคลาสมีอาวุธเริ่มต้นและสไตล์การเล่นเฉพาะตัว
* **ดาวเคราะห์และสภาพอากาศพลวัต (Biomes & Dynamic Weather):**
  * **Earth & Mars:** ตะลุยด่านเอาชีวิตรอด 40 Waves ในแต่ละดาว
  * **ระบบสภาพอากาศแปรปรวน:** รับมือกับ *Acid Rain (ฝนกรด)*, *Ion Tempest (พายุไอออน)*, *Haboob Dust Storm (พายุฝุ่นดาวอังคาร)* และ *Meteor Bombardment (ฝนดาวตก)* ที่ส่งผลต่อการเล่นจริง
* **ระดับความยาก 3 ระดับ:** ท้าทายฝีมือตั้งแต่โหมด **Normal**, **Hard** ไปจนถึง **Nightmare**
* **ระบบอัปเกรดและวิวัฒนาการอาวุธ (Weapon Evolution & Forge):**
  * สะสมแร่จากดาวเคราะห์ (*Iron, Quartz, Crimson, Solaris*) เพื่อคราฟต์และอัปเกรดชุดเกราะใน **Armory** และวิจัยค่าพลังใน **Research**
  * ผสมผสานไอเทมเพื่อปลดล็อก **Evolved Weapons** (อาวุธขั้นสุดยอด)
* **สารานุกรมข้อมูล (Codex Compendium):** รวบรวมข้อมูลภารกิจ (Quests), อาวุธ, สกิล (Perks) และสูตรวิวัฒนาการอาวุธครบจบในหน้าเดียว
* **รองรับการเล่นทุกอุปกรณ์:** ปรับหน้าจอแบบ Responsive พร้อมปุ่มควบคุมแบบ Touch Controls สำหรับมือถือและแท็บเล็ตโดยเฉพาะ

---

## 🛠️ เทคโนโลยีที่ใช้พัฒนา (Tech Stack)

* **Core Engine:** HTML5 Canvas, TypeScript / JavaScript
* **Audio System:** Web Audio API (Procedural Sound Effects & BGM)
* **Frontend & Build Tool:** React, Vite

---

## 💻 วิธีติดตั้งและรันโปรเจกต์ในเครื่อง (Run Locally)

1. **โคลนโปรเจกต์ (Clone Repository):**
   ```bash
   git clone [https://github.com/NueaMe/planetary-survivors.git](https://github.com/NueaMe/planetary-survivors.git)
   cd planetary-survivors
