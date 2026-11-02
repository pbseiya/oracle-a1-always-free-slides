# Oracle VM.Standard.A1.Flex — Always Free Slides

สไลด์สอนสด (Live Online) วันพุธที่ 4 พฤศจิกายน 2569 เวลา 20:00–21:00 น.
โดย Pongsak Boonpalit

เปิดสไลด์: https://pbseiya.github.io/oracle-a1-always-free-slides/

สไลด์เสริม — วิธีสมัคร Oracle Cloud Free Tier ทีละขั้นจากหน้าจอจริง (8 ขั้นตอน ภาพทั้งหมดปิดข้อมูลส่วนตัวแล้ว): https://pbseiya.github.io/oracle-a1-always-free-slides/signup.html

## เนื้อหา (24 สไลด์)
1. สมัคร Oracle Cloud Always Free — Home Region ap-singapore-1, โควตา A1 รวม 2 OCPU / 12 GB RAM, boot volume รวม 200 GB
2. ตั้งค่า Network ให้มี Public IPv4 — Create VCN with Internet Connectivity, Public Subnet, Internet Gateway, Security List (22/80/443)
3. สร้าง VM.Standard.A1.Flex Instance — Image ARM, Assign public IPv4, SSH key, ตรวจ Public IP และ Troubleshooting
4. Tips: อัปเกรด Pay As You Go เพิ่มโอกาสได้เครื่อง — ใช้เกินโควตา Always Free มีค่าใช้จ่ายจริง พร้อม Guardrail คุมงบ
5. ภาคเสริม OCI CLI — ติดตั้ง, `oci setup config`, สร้าง/จัดการ Instance ผ่าน API ให้ AI Agent ทำงานแทนอย่างปลอดภัย
6. ติดตั้ง Hermes Agent บน Oracle Linux 9 — ต่างจาก Ubuntu ตรงที่ใช้ `dnf` ไม่ใช่ `apt`: เตรียมแพ็กเกจพื้นฐานด้วย `sudo dnf install`, เปิด EPEL สำหรับ ripgrep, แล้วติดตั้งด้วยสคริปต์ทางการจาก GitHub (NousResearch/hermes-agent) และตั้งค่าด้วย `hermes setup` / `hermes doctor`

> ตัวอย่างคำสั่งทั้งหมดใช้ placeholder (เช่น `<COMPARTMENT_OCID>`, `<Public-IP>`, `<HERMES_TOKEN>`) ไม่มี credential จริงในไฟล์นี้
