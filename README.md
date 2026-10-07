<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    UsbDiskDoctor README                      -->
<!--                  Bilingual: Arabic + English                 -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://raw.githubusercontent.com/YOUR_USERNAME/UsbDiskDoctor/main/src/UsbDiskDoctor.App/Assets/app.ico" width="120" alt="UsbDiskDoctor Logo"/>

<h1>🩺 UsbDiskDoctor</h1>

<h3>طبيب الفلاشات وأقراص USB &nbsp;•&nbsp; USB Drive Diagnostic Tool</h3>

<p><strong>فحص • تشخيص • استعادة • إصلاح</strong><br/>
<em>Diagnose • Detect • Recover • Repair</em></p>

<!-- ═══════════ BADGES ═══════════ -->
<p>
  <img src="https://img.shields.io/badge/version-1.4.0-blue?style=for-the-badge" alt="Version"/>
  <img src="https://img.shields.io/badge/.NET-8.0-purple?style=for-the-badge&logo=dotnet" alt=".NET"/>
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows" alt="Platform"/>
  <img src="https://img.shields.io/badge/tests-137%20passing-brightgreen?style=for-the-badge&logo=xunit" alt="Tests"/>
  <img src="https://img.shields.io/badge/languages-AR%20%2B%20EN-orange?style=for-the-badge&logo=googletranslate" alt="Bilingual"/>
  <img src="https://img.shields.io/badge/license-Free%20Personal-green?style=for-the-badge" alt="License"/>
</p>

<p>
  <a href="#-العربية"><img src="https://img.shields.io/badge/🇮🇶_العربية-00A651?style=for-the-badge" alt="Arabic"/></a>
  <a href="#-english"><img src="https://img.shields.io/badge/🇬🇧_English-012169?style=for-the-badge" alt="English"/></a>
</p>

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ARABIC SECTION                            -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h1 id="-العربية" align="center">🇮🇶 العربية</h1>

<div dir="rtl">

## 🎯 ما هو UsbDiskDoctor؟

> **UsbDiskDoctor** أداة عراقية تعمل على Windows، وظيفتها **فحص وتشخيص وإصلاح** وحدات التخزين الخارجية.
>
> **بدون إنترنت • بالعربية والإنجليزية • بواجهة حديثة**

</div>

<div dir="rtl">

### ✨ الميزات الرئيسية

| 🎯 الميزة | 📝 التفصيل |
|:---------|:-----------|
| 🔍 **الاكتشاف والفحص** | كشف أجهزة USB عبر WMI (بما فيها UASP HDDs) مع تفاصيل كاملة |
| 🏥 **الفحص الصحي** | S.M.A.R.T. + فحص نظام الملفات + 12+ قاعدة تشخيص |
| 🎯 **كشف الفلاشات المزيفة** | كتابة أنماط اختبار على كامل السعة + كشف wraparound |
| 💾 **استعادة الملفات** | نسخ آمن + File Carving (JPEG/PNG/PDF) |
| 🛠️ **الإصلاح الآمن** | 3 مستويات خطر + Whitelist صارم + تأكيد إلزامي |
| 📄 **التقارير** | HTML (عربي RTL) + JSON |
| 📚 **قاعدة المعرفة** | 9 مقالات عربية (SMART، RAW، المزيفة، إلخ) |

</div>

<div dir="rtl">

### 🚀 البدء السريع

```bash
# 1) حمّل UsbDiskDoctor-Setup-v1.4.0.exe من Releases
# 2) شغّله (سيطلب UAC — يحتاج صلاحيات admin)
# 3) اتبع خطوات التثبيت
# 4) سيظهر الاختصار على سطح المكتب
```

**المتطلبات:**
- ✅ Windows 10/11 (64-bit)
- ✅ **لا يحتاج .NET runtime** (self-contained)
- ✅ WebView2 Runtime (مثبّت افتراضياً في Windows الحديث)

</div>

> [!IMPORTANT]
> **ملاحظة مهمة:** هذا البرنامج **أداة تشخيص واستعادة منطقية**. يعالج المشاكل البرمجية والداخلية، لكن **لا يقدر يصلح الأعطال الفيزيائية** (رأس هارد مكسور، ضربة قوية، إلخ). في مثل هذي الحالات، يوصيك تروح لمختبر نظيف.

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ENGLISH SECTION                           -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h1 id="-english" align="center">🌍 English</h1>

## 🎯 What is UsbDiskDoctor?

> **UsbDiskDoctor** is an Iraqi Windows tool for **diagnosing, examining, and repairing** external storage devices.
>
> **Offline • Bilingual (AR + EN) • Modern UI**

### ✨ Key Features

| 🎯 Feature | 📝 Details |
|:----------|:-----------|
| 🔍 **Discovery** | WMI-based USB detection (including UASP external HDDs) with full details |
| 🏥 **Health Check** | S.M.A.R.T. + file system checks + 12+ diagnostic rules |
| 🎯 **Fake Capacity Detection** | Writes test patterns across full capacity + wraparound detection |
| 💾 **File Recovery** | Safe copy + File Carving (JPEG/PNG/PDF) |
| 🛠️ **Safe Repair** | 3 risk levels + strict whitelist + mandatory confirmation |
| 📄 **Reports** | HTML (Arabic RTL) + JSON |
| 📚 **Knowledge Base** | 9 articles (SMART, RAW, fake drives, etc.) |

### 🚀 Quick Start

```bash
# 1) Download UsbDiskDoctor-Setup-v1.4.0.exe from Releases
# 2) Run it (UAC prompt will appear — admin required)
# 3) Follow installer steps
# 4) Desktop shortcut will be created
```

**Requirements:**
- ✅ Windows 10/11 (64-bit)
- ✅ **No .NET runtime required** (self-contained)
- ✅ WebView2 Runtime (pre-installed on modern Windows)

> [!IMPORTANT]
> **Important:** This is a **logical diagnostic and recovery tool**. It handles software and firmware-level issues, but **CANNOT fix physical failures** (broken HDD head, impact damage, etc.). For such cases, consult a clean-room specialist.

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    COMMON SECTIONS                           -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">📸 Screenshots</h2>

<p align="center">
  <img src="docs/screenshots/main-window-ar.png" width="45%" alt="Arabic UI"/>
  &nbsp;&nbsp;
  <img src="docs/screenshots/main-window-en.png" width="45%" alt="English UI"/>
</p>

<p align="center">
  <img src="docs/screenshots/capacity-check.png" width="45%" alt="Capacity Check"/>
  &nbsp;&nbsp;
  <img src="docs/screenshots/contact-window.png" width="45%" alt="Contact Window"/>
</p>

> 📌 **ملاحظة**: الصور ستُضاف بعد أول رفع للمشروع على GitHub.
> **Note**: Screenshots will be added after first upload.

---

<h2 align="center">🏗️ Architecture</h2>

<div align="center">

**10 Projects** &nbsp;•&nbsp; **7 Libraries + 3 Test Projects**

</div>

| Project | TFM | Tests | Role |
|:--------|:---:|:-----:|:-----|
| `UsbDiskDoctor.App` | `net8.0-windows` | — | WPF UI (Bilingual) |
| `UsbDiskDoctor.Core` | `net8.0` | — | Models, Enums, Logging |
| `UsbDiskDoctor.Diagnostics` | `net8.0-windows` | — | Discovery, Health, WMI |
| `UsbDiskDoctor.Repair` | `net8.0-windows` | — | Planning, Safe Execution |
| `UsbDiskDoctor.Recovery` | `net8.0` | — | Scan, Restore, Carving, Capacity |
| `UsbDiskDoctor.Knowledge` | `net8.0` | — | Knowledge Base (JSON) |
| `UsbDiskDoctor.Reporting` | `net8.0-windows` | — | HTML/JSON Reports |
| `UsbDiskDoctor.Core.Tests` | `net8.0` | **55** | Core tests |
| `UsbDiskDoctor.Diagnostics.Tests` | `net8.0-windows` | **70** | Diagnostics tests |
| `UsbDiskDoctor.App.Tests` | `net8.0-windows` | **12** | ViewModels tests |

<div align="center">

**Stack**: WPF • MVVM (CommunityToolkit) • System.Management (WMI) • WebView2 • Serilog

</div>

---

<h2 align="center">🛡️ Security</h2>

<div align="center">

| 🔒 | الميزة | Feature |
|:--:|:-------|:--------|
| ✅ | **لا كتابة بدون إذن صريح** | **No writes without explicit permission** |
| ✅ | **قائمة بيضاء للأوامر** | **Strict command whitelist** |
| ✅ | **منع الكتابة على القرص المصدر** | **Blocks writing to source drive** |
| ✅ | **Timeout إجباري** | **Mandatory timeout** |
| ✅ | **سجل تدقيق كامل** | **Full audit log** |
| ✅ | **UAC manifest** | **UAC manifest (auto-elevation)** |

</div>

---

<h2 align="center">🌍 Bilingual Support</h2>

<div align="center">

<table>
<tr>
<td align="center" width="50%">

### 🇮🇶 العربية

- واجهة عربية **RTL**
- زر 🌐 لتغيير اللغة
- الاختيار يُحفظ في Windows Registry
- ~120 مفتاح ترجمة
- تقارير عربية

</td>
<td align="center" width="50%">

### 🇬🇧 English

- **LTR** English UI
- 🌐 button to switch
- Choice saved in Windows Registry
- ~120 translation keys
- English installer README

</td>
</tr>
</table>

</div>

---

<h2 align="center">📊 Test Coverage</h2>

<div align="center">

### **137 / 137** ✅

![Core Tests](https://img.shields.io/badge/Core.Tests-55%20passing-brightgreen)
![Diagnostics Tests](https://img.shields.io/badge/Diagnostics.Tests-70%20passing-brightgreen)
![App Tests](https://img.shields.io/badge/App.Tests-12%20passing-brightgreen)

</div>

<details>
<summary><b>📋 عرض تفاصيل الاختبارات / Show test details</b></summary>

**Coverage includes:**
- ✅ Models & Enums validation
- ✅ Health rules engine (14 rules)
- ✅ Repair planning (13 tests)
- ✅ Safe execution (10 tests)
- ✅ File carving (JPEG/PNG/PDF)
- ✅ Capacity check (20 tests)
- ✅ ViewModels (12 tests)
- ✅ MediaType inference (24 tests)

</details>

---

<h2 align="center">👨‍💻 Developer</h2>

<div align="center">

### **Mahmoud Al-Aboudi** — محمود العبوده

**Basra, Iraq** 🇮🇶 **•** **البصرة، العراق**

<br/>

<a href="https://wa.me/9647730393399">
  <img src="https://img.shields.io/badge/WhatsApp-009647730393399-25D366?style=for-the-badge&logo=whatsapp" alt="WhatsApp"/>
</a>
&nbsp;
<a href="mailto:tearscantstop@gmail.com">
  <img src="https://img.shields.io/badge/Email-tearscantstop@gmail.com-EA4335?style=for-the-badge&logo=gmail" alt="Email"/>
</a>

</div>

---

<h2 align="center">📜 License</h2>

<div align="center">

**Free for personal use** — مجاني للاستخدام الشخصي

<img src="https://img.shields.io/badge/License-Free%20Personal%20Use-green?style=for-the-badge" alt="License"/>

</div>

---

<h2 align="center">⚠️ Important Notes / تنبيهات مهمة</h2>

> [!WARNING]
> **🇮🇶** لا تستخدم البرنامج على أقراص سليمة بها بيانات مهمة بدون نسخة احتياطية. البرنامج أداة تشخيص — استخدمه بحذر.
>
> **🇬🇧** Do not use on healthy drives with important data without a backup. This is a diagnostic tool — use it carefully.

> [!CAUTION]
> **🇮🇶** للحالات الحرجة (Click of Death، Size=0): استشر مختص في مختبر نظيف. البرنامج لا يصلح الأعطال الفيزيائية.
>
> **🇬🇧** For critical cases (Click of Death, Size=0): consult a clean-room specialist. Physical failures cannot be fixed by software.

> [!TIP]
> **🇮🇶** هل تريد التأكد أن فلاشتك أصلية؟ استخدم "فحص السعة الحقيقية" من Tab التفاصيل — 10 ثواني تكشف أي فلاشة مزيفة.
>
> **🇬🇧** Want to verify a flash drive is genuine? Use "Real Capacity Check" from the Details tab — 10 seconds to detect any fake drive.

---

<div align="center">

<h3>🌟 Support the Project</h3>

<p>إذا أعجبك البرنامج، لا تنسى تعطينا ⭐ على GitHub!</p>
<p><em>If you like the tool, don't forget to give us a ⭐ on GitHub!</em></p>

<br/>

<h3>🤝 Contributing / المساهمة</h3>

<p>Pull requests are welcome! For major changes, please open an issue first.</p>
<p><em>طلبات السحب مُرحّب بها! للتغييرات الكبيرة، يرجى فتح issue أولاً.</em></p>

<br/>

<hr/>

<h3>💚 Made with Love in Basra, Iraq</h3>

<p><strong>صُنع بـ ❤️ في البصرة، العراق</strong></p>

<p><sub>v1.4.0 • 2026-10-07 • © Mahmoud Al-Aboudi</sub></p>

</div>
