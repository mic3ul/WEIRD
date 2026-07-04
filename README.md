# WEIRDO | KLAUS 🦎

اداة  شاملة  تشتغل على تيرمكس
من قيس ويردو

### طيب وش فيها

 اكثر من 47 وحدة تشغيلية.. 
 مولّد حمولات عكسية وويب شيل
 فحص  لثغرات الويب.. SQLi و XSS و LFI و Command Injection
 استطلاع شامل DNS و Subdomain و Port Scan و OSINT و Google Dorks
مستمع متعدد العملاء وخادم HTTP و HTTPS لنقل الملفات
 ادوات استغلال منها تصعيد الصلاحيات وجمع بيانات الدخول وهجمات تخمين
 فحص الشبكات ARP Scan و Ping Sweep و Slowloris وتغيير MAC وبروكسي Tor

---

### خطوات التثبيت 

#### ١. تحديث تيرمكس وتثبيت الأدوات الأساسية
```bash
pkg update -y && pkg upgrade -y
pkg install python git -y
```

٢. تثبيت مترجم clang ومكتبات البناء (ضروري لتثبيت pycryptodome)

```bash
pkg install clang python-dev openssl libffi -y
```

٣. تثبيت مكتبة التشفير pycryptodome

```bash
pip install pycryptodome
```

لو واجهت مشكلة في التثبيت، تأكد إنك مثبت clang وأعد المحاولة.

٤. استنساخ المستودع

```bash
git clone https://github.com/mic3ul/WEIRD.git
cd WEIRD
```

٥. تشغيل الأداة (التثبيت التلقائي لبقية المتطلبات)

```bash
python WEIRDO.py
```

الأداة بتثبت أي مكتبات ناقصة تلقائياً في أول تشغيل.

---

الاستخدام اليومي

بعد التثبيت، افتح تيرمكس واكتب:

```bash
cd WEIRD
python WEIRDO.py
```

بتظهر لك القائمة الرئيسية:

```text
 1.  Reconnaissance          8.  Set Target
 2.  Web Attacks             9.  View Saved Results
 3.  Payload Generator      10.  Install Dependencies
 4.  Listener               11.  Clear Workspace
 5.  Phishing Kit           12.  Show Network Info
 6.  Exploitation           13.  Update KLAUS | WEIRDO
 7.  Network Attacks         0.  Exit
```

اختار الرقم وحدد الهدف وامش مع الأوامر.

---

الملف المشفر

الملف المرفوع نسخة مشفرة من الأداة
لما تشغله بيطلب منك كلمة سر

لطلب كلمة السر لفك التشفير راسلني على تيليجرام
@ttetie

---

المطور

mic3ul
للتواصل تيليجرام @ttetie
```link
https://t.me/+2_pbiurDNw8zMDJk

