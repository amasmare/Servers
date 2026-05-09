# مختبرات CompTIA Server+ التفاعلية
### Interactive CompTIA Server+ Labs

---

## 🇸🇦 بالعربية

### نبذة عن المشروع

هذا المشروع عبارة عن منصة تدريبية تفاعلية مبنية بالكامل باستخدام HTML وCSS وJavaScript، صُممت لمساعدة الطلاب على التحضير لاختبار **CompTIA Server+ (SK0-005)**.

تحوّل كل مفهوم نظري من منهج الشهادة إلى محاكاة عملية تعمل مباشرةً في المتصفح — دون الحاجة لأي إنترنت أو تثبيت برامج.

### الهدف من المشروع

- **تعليمي أكاديمي بحت** — مساعدة طلاب تقنية المعلومات على فهم مواضيع الخوادم بطريقة تفاعلية عملية
- تغطية جميع فصول منهج Server+ الـ 11 بمختبر تفاعلي لكل فصل
- تتبع تقدم الطالب وحفظ نتائجه محلياً
- إمكانية مشاركة التقرير مع أستاذ المادة

### المختبرات (11 فصلاً + اختبار شامل)

| # | المختبر | الموضوع |
|---|---------|---------|
| 1 | التعرف على عتاد الخوادم | عوامل الشكل، المكونات، المواصفات |
| 2 | BIOS/UEFI وإعداد الخادم | محاكاة إعدادات البرامج الثابتة، POST |
| 3 | ضبط RAID وحسابات التخزين | مستويات RAID، السعة، تحمّل الأعطال |
| 4 | تقنيات التخزين | DAS/NAS/SAN، iSCSI، Fibre Channel |
| 5 | اتصالات الشبكات | نموذج OSI، الكابلات، IPv4/IPv6، TCP/UDP، DHCP/DNS |
| 6 | أدوار الخوادم والخدمات | DNS، DHCP، AD، أرقام المنافذ |
| 7 | الافتراضية | Hypervisor النوع I/II، الترحيل المباشر، اللقطات |
| 8 | أمن الخوادم وتقويته | PKI، الأمن المادي، MFA، ضوابط الوصول |
| 9 | أمن الشبكات | جدران الحماية، VLAN، VPN، IDS/IPS، DMZ |
| 10 | التعافي من الكوارث | RTO/RPO، المواقع الساخنة/الدافئة/الباردة، النسخ الاحتياطي |
| 11 | استكشاف الأخطاء | المنهجية السباعية، أدوات التشخيص |
| ★ | الاختبار الشامل النهائي | جميع المحاور — تحدي متعدد المراحل |

### المميزات التقنية

- ✅ يعمل بالكامل في المتصفح — لا إنترنت ولا تثبيت
- ✅ يدعم جميع الأجهزة: Windows، Mac، iPad، iPhone، Android
- ✅ حفظ النتائج محلياً عبر `localStorage`
- ✅ نظام تقارير قابل للمشاركة مع الأستاذ عبر رابط أو تيليغرام
- ✅ واجهة عربية كاملة (RTL) مع دعم اللغة العربية
- ✅ تصميم داكن احترافي مناسب للبيئات التقنية

### صاحب المشروع

**م. عبدالله الأسمري — Eng. Abdullah Alasmari**
مختبرات Server+ التفاعلية · للاستخدام الأكاديمي

---

## 🇬🇧 In English

### About the Project

This project is a fully browser-based interactive training platform built with HTML, CSS, and JavaScript, designed to help students prepare for the **CompTIA Server+ (SK0-005)** certification exam.

Every theoretical concept from the certification syllabus is transformed into a hands-on interactive simulation that runs directly in the browser — no internet connection or software installation required.

### Purpose

- **Purely academic and educational** — helping IT students understand server concepts through practical, interactive simulations
- Full coverage of all 11 chapters of the Server+ curriculum, with one dedicated interactive lab per chapter
- Student progress tracking with locally-saved scores
- Shareable report system so students can send results to their instructor

### Labs (11 Chapters + Final Capstone)

| # | Lab | Topics Covered |
|---|-----|----------------|
| 1 | Server Hardware Identification | Form factors, components, specifications |
| 2 | BIOS/UEFI & Server Setup | Firmware settings simulation, POST codes |
| 3 | RAID Configuration & Storage Calculations | RAID levels, capacity, fault tolerance |
| 4 | Storage Technologies | DAS/NAS/SAN, iSCSI, Fibre Channel |
| 5 | Network Communications | OSI model, cables, IPv4/IPv6, TCP/UDP, DHCP/DNS |
| 6 | Server Roles & Services | DNS, DHCP, AD, port numbers |
| 7 | Virtualization | Type I/II hypervisors, live migration, snapshots |
| 8 | Server Security & Hardening | PKI, physical security, MFA, access controls |
| 9 | Network Security | Firewalls, VLAN, VPN, IDS/IPS, DMZ |
| 10 | Disaster Recovery | RTO/RPO, hot/warm/cold sites, backup strategies |
| 11 | Troubleshooting Methodology | CompTIA 7-step process, diagnostic tools |
| ★ | Final Capstone Challenge | All topics — multi-stage scenario |

### Technical Features

- ✅ Runs entirely in the browser — no internet or installation needed
- ✅ Supports all devices: Windows, Mac, iPad, iPhone, Android
- ✅ Scores saved locally via `localStorage`
- ✅ Shareable student report system via link or Telegram
- ✅ Full Arabic RTL interface with bilingual support
- ✅ Professional dark UI suitable for technical environments

### Project Structure

```
/
├── index.html                    # Main page — lab directory
├── hardware-lab.html             # Lab 01 — Server Hardware
├── bios-setup-lab.html           # Lab 02 — BIOS/UEFI
├── raid-lab.html                 # Lab 03 — RAID
├── storage-lab.html              # Lab 04 — Storage Technologies
├── network-communications-lab.html  # Lab 05 — Network Communications
├── server-roles-lab.html         # Lab 06 — Server Roles
├── virtualization-lab.html       # Lab 07 — Virtualization
├── security-hardening-lab.html   # Lab 08 — Security Hardening
├── network-security-lab.html     # Lab 09 — Network Security
├── disaster-recovery-lab.html    # Lab 10 — Disaster Recovery
├── troubleshooting-lab.html      # Lab 11 — Troubleshooting
└── capstone-lab.html             # Final Capstone Challenge
```

### Author

**Eng. Abdullah Alasmari — م. عبدالله الأسمري**
CompTIA Server+ Interactive Labs · For Academic Use Only

---

> © 2025 · All content is for educational and academic purposes only
> استناداً إلى شهادة **CompTIA Server+ SK0-005**
