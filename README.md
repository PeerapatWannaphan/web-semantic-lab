# Web Semantic Lab
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development
## รายละเอียด
- การใช้ Semantic HTML
- Form Validation
- ARIA Labels
## ส่วนที่ 1: การเตรียมโปรเจค
- git clone https://github.com/Fluxseafood/web-semantic-lab.git
- git add README.md
- git commit -m "comment"
- git push
## ส่วนที่ 2: สร้าง branch สําหรับพัฒนา
- git checkout -b development
- git add .
- git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"
## ส่วนที่ 3: สร้าง branch สําหรับพัฒนา
- git checkout -b feature/homepage
- git add index.html
- git add commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค"
## ส่วนที่ 4: การพัฒนาหน้าหลักด ้วย Semantic HTML
- git add index.html
- git add commit -m "เพิ่ม header และ nav ในหน้าหลัก"
- git add index.html
- git add commit -m "เพิ่มส่วน main และ article ในหน้าหลัก"
- git add index.html
- git add commit -m "เพิ่ม aside และ footer ในหน้าหลัก"
## ส่วนที่ 5: การสร้างฟอร์มติดต่อพร้อม Validation
- git checkout development
- git checkout -b feature/contact
- git add contact.html
- git add commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
- git add contact.html
- git add commit -m "เพิ่มฟอร์มพื้นฐานในหน้าติดต่อ"
- git add contact.html
- git add commit -m "เพิ่ม validation ในฟอร์มติดต่อ"
## ส่วนที่ 6: การเพิ่ม ARIA Labels
- git add contact.html
- git add commit -m "เพิ่ม ARIA labels ในฟอร์ม"
- git add .
- git add commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
- git merge feature/homepage
- git merge feature/contact
- git push origin development
