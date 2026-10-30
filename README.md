<div align="center">

# 🌐 VPN Scan
**Made by (R.S)**

فارسی · [English](#english) · [العربية](#العربية) · [中文](#中文) · [Русский](#русский)

</div>

---

<div dir="rtl">

# 🌐 VPN Scan — یابنده، تست‌کننده و VPN سرورهای V2Ray

برنامهٔ اندروید برای پیدا کردن، **تست واقعی** و وصل شدن به سرورهای سالم V2Ray؛ ساخته‌شده برای شبکه‌های پرمحدودیت، از اینترنت آزاد تا نت ملی. هیچ سروری داخل برنامه نیست؛ خودش از منابع عمومی کانفیگ پیدا و تست می‌کند.

## ⬇️ دانلود
آخرین نسخه را از بخش **Releases** دانلود و نصب کن:
- `VPN-Scan-universal.apk` — **اگر نمی‌دانی گوشی‌ات چیست، همین را بگیر** (روی همهٔ گوشی‌ها کار می‌کند)
- `VPN-Scan-arm64.apk` — گوشی‌های جدید (۶۴ بیتی)، کوچک‌تر
- `VPN-Scan-arm32.apk` — گوشی‌های قدیمی (۳۲ بیتی)

اندروید ۸ به بالا · گوشی‌های ۶۴ بیتی برای همهٔ امکانات.

## 🧠 سه هسته (هستهٔ اتصال)
کانفیگ‌ها با سه هستهٔ واقعی تست و اجرا می‌شوند و برای هر سرور معلوم می‌شود با کدام برنامه کار می‌کند:
- **Xray** — همان هستهٔ **v2rayNG** و **V2Box**
- **Xray 25** — همان هستهٔ **NPV Tunnel**
- **sing-box** — همان هستهٔ **Hiddify**
- **خودکار:** بهترین هسته را برای هر سرور خودش انتخاب می‌کند.

کنار هر سرور برچسبی نشان می‌دهد با کدام برنامه‌ها کار می‌کند (سالم = سبز، ناسازگار = خط‌خورده).

## 🔎 پیدا کردن و تست کانفیگ
- کانفیگ‌های رایگان از **منابع عمومی متعدد**، با آینه و **DNS امن (DoH)** وقتی مسیری بسته است.
- همهٔ پروتکل‌ها: **VLESS، VMess، Trojan، Shadowsocks، Hysteria2، Hysteria، TUIC، WireGuard، AnyTLS، SOCKS**.
- **تست واقعی (نه فقط پینگ):** هر کانفیگ واقعاً با هسته بالا می‌آید و به اینترنت وصل می‌شود؛ پینگ خارج و داخل و پایداری با دو تست سنجیده می‌شود.
- نتیجه در سه دسته: **سالم / تست‌شده / رد شده** با دلیل رد.

## 🚀 تست سرعت
بعد از اسکن، سرورهای برتر **تست سرعت دانلود واقعی** می‌شوند؛ خودکار (۱۰ سرور اول) یا دستی.

## 🌐 تست دسترسی (تلگرام / اینستاگرام / یوتیوب / گوگل)
روی هر سرور دکمه‌های **Telegram، Instagram، YouTube، Google**؛ همان لحظه تست می‌شود که آن سرویس از این سرور باز می‌شود یا نه.

## 📶 اطلاعات اپراتور و شبکه
**IP، اپراتور** (همراه اول، ایرانسل، مخابرات، آپتل، سامانتل، شاتل، یا تشخیص خودکار)، **موقعیت، شبکه (ISP)، پینگ خارج/داخل، سرعت دانلود**؛ با سابقه و تنظیمات جدا برای هر اپراتور.

## ☁ IP تمیز کلودفلر
برای کانفیگ‌های CDN که دامنه/IP‌شان فیلتر است، یک **IP تمیز کلودفلر** از بانک بزرگ پیدا و جایگزین می‌شود.

## ✂ فرگمنت
اولین بستهٔ **TLS** تکه‌تکه می‌شود تا DPI از روی SNI سرور را نشناسد و نبندد؛ قابل تنظیم.

## ⭐ سرورهای منتخب
ستاره‌دار کردن سرورها؛ بالای فهرست، تست دوره‌ای، و اولویت در اتصال.

## 🛡 VPN داخلی
اتصال یک‌لمسی به بهترین سرور، **جابه‌جایی خودکار** هنگام قطع، **اتصال مجدد خودکار**، **Kill Switch**؛ حالت **VPN** یا فقط **پروکسی SOCKS/HTTP**، اشتراک **LAN**، کاشی Quick Settings، آمار ترافیک زنده در اعلان.

## 🧭 مسیریابی و داده‌ها
**بای‌پس داخلی** (سایت/IP داخلی مستقیم + فهرست دلخواه)، **Split Tunneling** (فقط/به‌جز برنامه‌های انتخابی)، **دسترسی به شبکهٔ محلی**، **مدیریت مصرف** با هشدار سقف.

## 👤 پروفایل‌ها
چند پروفایل جدا (خانه، همراه اول…)؛ هر کدام حالت اینترنت، اپراتور، تنظیمات اسکن، فرگمنت، IP تمیز، سایت‌های داخلی، برنامه‌ها و تنظیمات اتصال را جدا نگه می‌دارد.

## 🔒 امنیت و حفاظت
**Kill Switch**، **اتصال مجدد خودکار** (اول منتخب‌ها بعد سریع‌ترین‌ها)، **قفل در سطح گوشی** (VPN همیشه‌روشن + مسدودکردن اتصال بدون VPN)، **بهینه‌سازی باتری**.

## ⚙ تنظیمات اتصال
نوع تونل، هسته، **MTU**، **Mux**، **فرگمنت**، **QUIC داخل VPN**، **IPv6 داخل تونل** (پیش‌فرض خاموش)، سطح لاگ.

## 🔎 تنظیمات اسکن
حالت اسکن (**سریع/متعادل/کامل**)، نسخهٔ IP، **تست سرعت خودکار**، **اسکن خودکار** (۳/۶/۱۲ ساعت)، تعداد سرور.

## 🛰 نت ملی (وقتی اینترنت بین‌الملل قطع است)
به‌ترتیب این مسیرها (قابل روشن/خاموش و جابه‌جایی):
1. **مستقیم** — از اینترنت خود گوشی (با DoH و آینه‌ها).
2. **فرگمنت** — تکه‌تکه کردن TLS برای رد شدن از فیلتر SNI.
3. **سرورهای ذخیره‌شده** — از سرورهای سالمی که قبلاً پیدا شده‌اند.
4. **پروکسی** — پروکسی SOCKS/HTTP خودت.
5. **thefeed** — کانال‌های تلگرام از راه DNS.
6. **تونل DNS** — Soar / MasterDNS / Cotten / StormDNS.

## 🧩 تونل DNS و موتورها
وقتی حتی DNS کار می‌کند ولی بقیهٔ اینترنت نه، داده **از داخل کوئری‌های DNS** رد می‌شود. چهار موتور: **MasterDNS، StormDNS، CottenDNS (و CottenMax)، Soar**. **پروفایل سرور خودت** را وارد می‌کنی (هیچ سروری داخل برنامه نیست)، چند سرور، انتخاب سرور، و **VPN از راه تونل**.

## 🧭 رزولورها
**بانک بزرگ رزولور آماده** + **یابندهٔ رزولور سالم** + **کشف رزولور جدید** از رنج‌های IP داخلی؛ موتور قبل از استفاده رزولورها را وارسی می‌کند.

## 📡 thefeed
خواندن **کانال‌های تلگرام از راه DNS**: فهرست کانال‌ها و پیام‌ها، **دریافت عکس و فایل**، **خواندن QR**، و لینک/پروکسی قابل‌لمس. (سرور thefeed را هم خودت وارد می‌کنی.)

## 🔌 OpenVPN
پشتیبانی از سرورهای عمومی OpenVPN و فایل‌های `.ovpn` با **تست واقعی دست‌دهی**.

## 📤 اشتراک
ارسال کانفیگ به گوشی دیگر (**QR/فایل/متن/کد**) و دریافت، **ارسال خود برنامه بدون اینترنت**، تشخیص از کلیپ‌بورد، آپدیت از هر مسیر باز.

## 🎨 دیگر
پنج زبان · تم تیره/روشن/خودکار · لاگ و گزارش کامل.

## 🔒 حریم خصوصی
برنامه هیچ سرور، دامنه یا کلیدی از سازنده ندارد؛ پروفایل‌ها را خودت وارد می‌کنی و فقط روی گوشی خودت می‌مانند. هیچ اطلاعاتی از کاربر به جایی فرستاده نمی‌شود.

## 🔒 کد برنامه
کد این برنامه خصوصی است و منتشر نمی‌شود.

## 📜 مجوزها
از نرم‌افزارهای متن‌باز استفاده شده؛ فهرست و مجوزها در [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

</div>

---

## English

# 🌐 VPN Scan — find, test & connect to working V2Ray servers

An Android app to find, **really test** and connect to working V2Ray servers — built for heavily restricted networks, from the open internet to a national intranet. No servers ship in the app; it finds and tests configs from public sources itself.

## ⬇️ Download
Get the latest build from **Releases**:
- `VPN-Scan-universal.apk` — **if you don't know your phone, get this one** (works on all phones)
- `VPN-Scan-arm64.apk` — newer 64-bit phones, smaller
- `VPN-Scan-arm32.apk` — older 32-bit phones

Android 8+ · 64-bit phones for all features.

## 🧠 Three cores
Configs are really run and tested with three cores, and each server shows which app it works with:
- **Xray** — the same core as **v2rayNG** and **V2Box**
- **Xray 25** — the same core as **NPV Tunnel**
- **sing-box** — the same core as **Hiddify**
- **Auto:** picks the best core per server.

A badge on each server shows which apps it works with (working = green, incompatible = struck-through).

## 🔎 Finding & testing configs
- Free configs from **many public sources**, with mirrors and **secure DNS (DoH)** when a path is blocked.
- All protocols: **VLESS, VMess, Trojan, Shadowsocks, Hysteria2, Hysteria, TUIC, WireGuard, AnyTLS, SOCKS**.
- **Real testing (not just ping):** each config actually starts with a core and reaches the internet; ping (abroad/domestic) and stability (two tests) are measured.
- Results in three groups: **working / tested / rejected**, with rejection reasons.

## 🚀 Speed test
After a scan, the top servers get a **real download speed test**; automatic (first 10) or manual.

## 🌐 Reachability test (Telegram / Instagram / YouTube / Google)
Each server has **Telegram, Instagram, YouTube, Google** buttons to test right away whether that service opens through it.

## 📶 Operator & network info
**IP, operator** (auto-detected or chosen), **location, ISP, ping abroad/domestic, download speed**, with separate history and settings per operator.

## ☁ Cloudflare clean IP
For CDN configs whose domain/IP is blocked, a **clean Cloudflare IP** from a large bank is found and substituted.

## ✂ Fragmentation
The first **TLS** packet is split so DPI can't spot the server by SNI; configurable.

## ⭐ Favourite servers
Star servers to keep them on top, re-test them periodically and try them first on connect.

## 🛡 Built-in VPN
One-tap connect to the best server, **auto-switch** on drop, **auto-reconnect**, **kill switch**; **VPN** or **SOCKS/HTTP proxy** mode, **LAN** sharing, Quick Settings tile, live traffic stats in the notification.

## 🧭 Routing & data
**Domestic bypass** (local sites/IPs direct + your own list), **split tunnelling** (only/except selected apps), **LAN access**, **usage management** with a cap alert.

## 👤 Profiles
Several separate profiles (home, mobile…); each keeps its own internet mode, operator, scan settings, fragment, clean IPs, domestic sites, apps and connection settings.

## 🔒 Security & protection
**Kill switch**, **auto-reconnect** (favourites first, then fastest), **device-level lock** (always-on VPN + block connections without VPN), **battery optimisation**.

## ⚙ Connection settings
Tunnel type, core, **MTU**, **Mux**, **fragment**, **QUIC inside VPN**, **IPv6 inside the tunnel** (off by default), log level.

## 🔎 Scan settings
Scan mode (**fast/balanced/full**), IP version, **auto speed test**, **auto-scan** (every 3/6/12 h), number of servers.

## 🛰 National net (when international internet is cut)
It tries these paths in order (each can be toggled and reordered):
1. **Direct** — from the phone's own internet (with DoH and mirrors).
2. **Fragment** — TLS splitting to pass SNI filtering.
3. **Saved servers** — from previously found working servers.
4. **Proxy** — your own SOCKS/HTTP proxy.
5. **thefeed** — Telegram channels over DNS.
6. **DNS tunnel** — Soar / MasterDNS / Cotten / StormDNS.

## 🧩 DNS tunnel & engines
When even DNS works but the rest of the internet doesn't, data is carried **inside DNS queries**. Four engines: **MasterDNS, StormDNS, CottenDNS (and CottenMax), Soar**. You enter **your own server profile** (no servers ship in the app), keep several servers, pick one, and turn on **VPN over the tunnel**.

## 🧭 Resolvers
A **large built-in resolver bank** + a **healthy-resolver finder** + **discovery of new resolvers** from domestic IP ranges; the engine verifies resolvers before use.

## 📡 thefeed
Read **Telegram channels over DNS**: channel and message list, **fetch images and files**, **QR reading**, tappable links/proxies. (You enter your own thefeed server too.)

## 🔌 OpenVPN
Public OpenVPN servers and `.ovpn` files with **real handshake testing**.

## 📤 Sharing
Send configs to another phone (**QR/file/text/code**) and receive, **send the app itself offline**, auto-detect from the clipboard, update over any open path.

## 🎨 Other
Five languages · dark/light/auto themes · full logs.

## 🔒 Privacy
The app ships no servers, domains or keys from the author; you enter profiles yourself and they stay only on your phone. No user data is ever sent anywhere.

## 🔒 Source
The source code is private and not published.

## 📜 Licenses
Built with open-source software; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

---

<div dir="rtl">

## العربية

# 🌐 VPN Scan — البحث عن خوادم V2Ray واختبارها والاتصال بها

تطبيق أندرويد للعثور على خوادم V2Ray واختبارها **فعليًا** والاتصال بها؛ مُصمّم للشبكات شديدة التقييد، من الإنترنت الحر إلى الشبكة الوطنية المغلقة. لا توجد خوادم داخل التطبيق؛ يجد الإعدادات ويختبرها من مصادر عامة بنفسه.

## ⬇️ التنزيل
نزّل أحدث إصدار من **Releases**:
- `VPN-Scan-universal.apk` — **إن لم تكن تعرف نوع هاتفك فاختر هذا** (يعمل على كل الهواتف)
- `VPN-Scan-arm64.apk` — الهواتف الحديثة (64-بت)، أصغر
- `VPN-Scan-arm32.apk` — الهواتف القديمة (32-بت)

أندرويد 8 فأحدث · الهواتف 64-بت لكل الميزات.

## 🧠 ثلاث نوى
تُشغَّل الإعدادات وتُختبر فعليًا بثلاث نوى، ويظهر لكل خادم مع أي تطبيق يعمل:
- **Xray** — نفس نواة **v2rayNG** و**V2Box**
- **Xray 25** — نفس نواة **NPV Tunnel**
- **sing-box** — نفس نواة **Hiddify**
- **تلقائي:** يختار أفضل نواة لكل خادم.

## 🔎 البحث والاختبار
- إعدادات مجانية من **مصادر عامة متعددة**، مع مرايا و**DNS آمن (DoH)** عند حجب مسار.
- كل البروتوكولات: **VLESS، VMess، Trojan، Shadowsocks، Hysteria2، Hysteria، TUIC، WireGuard، AnyTLS، SOCKS**.
- **اختبار فعلي (لا مجرد Ping):** كل إعداد يعمل فعلًا بنواة ويصل إلى الإنترنت؛ قياس البينغ (خارجي/محلي) والثبات باختبارين.
- النتائج في ثلاث فئات: **سليم / مُختبَر / مرفوض** مع سبب الرفض.

## 🚀 اختبار السرعة
بعد الفحص، تخضع أفضل الخوادم **لاختبار سرعة تنزيل فعلي**؛ تلقائيًا (أول 10) أو يدويًا.

## 🌐 اختبار الوصول (تلغرام / إنستغرام / يوتيوب / جوجل)
لكل خادم أزرار **Telegram وInstagram وYouTube وGoogle** لاختبار فتح كل خدمة عبره فورًا.

## 📶 معلومات المشغّل والشبكة
**IP والمشغّل** (كشف تلقائي أو اختيار)، **الموقع وISP والبينغ خارجي/محلي وسرعة التنزيل**، مع سجل وإعدادات منفصلة لكل مشغّل.

## ☁ IP نظيف من Cloudflare
للإعدادات على CDN المحجوب نطاقها/عنوانها، يُعثر على **IP نظيف من Cloudflare** من بنك كبير ويُستبدَل.

## ✂ التجزئة (Fragment)
تُجزّأ أول حزمة **TLS** كي لا يتعرّف DPI على الخادم عبر SNI؛ قابلة للضبط.

## ⭐ الخوادم المفضّلة
تمييز الخوادم بنجمة لإبقائها في الأعلى وإعادة اختبارها دوريًا وتجربتها أولًا عند الاتصال.

## 🛡 VPN مدمج
اتصال بلمسة بأفضل خادم، **تبديل تلقائي** عند الانقطاع، **إعادة اتصال تلقائية**، **Kill Switch**؛ وضع **VPN** أو **وكيل SOCKS/HTTP**، مشاركة **LAN**، مربّع إعدادات سريعة، وإحصاءات حية في الإشعار.

## 🧭 التوجيه والبيانات
**تمرير محلي مباشر** (مواقع/عناوين محلية + قائمتك)، **تقسيم النفق** (فقط/باستثناء تطبيقات مختارة)، **وصول LAN**، **إدارة الاستهلاك** مع تنبيه سقف.

## 👤 الملفات الشخصية
عدة ملفات منفصلة (المنزل، الجوال…)؛ كل منها يحتفظ بوضع الإنترنت والمشغّل وإعدادات الفحص والتجزئة وعناوين IP النظيفة والمواقع المحلية والتطبيقات وإعدادات الاتصال.

## 🔒 الأمان والحماية
**Kill Switch**، **إعادة اتصال تلقائية** (المفضّلة أولًا ثم الأسرع)، **قفل على مستوى الهاتف** (VPN دائم + حظر الاتصال بدون VPN)، **تحسين البطارية**.

## ⚙ إعدادات الاتصال
نوع النفق، النواة، **MTU**، **Mux**، **التجزئة**، **QUIC داخل VPN**، **IPv6 داخل النفق** (مُطفأ افتراضيًا)، مستوى السجل.

## 🔎 إعدادات الفحص
وضع الفحص (**سريع/متوازن/كامل**)، إصدار IP، **اختبار سرعة تلقائي**، **فحص تلقائي** (كل 3/6/12 ساعة)، عدد الخوادم.

## 🛰 الشبكة الوطنية (عند قطع الإنترنت الدولي)
يجرّب هذه المسارات بالترتيب (كلٌّ قابل للتشغيل/الإطفاء وإعادة الترتيب):
1. **مباشر** — من إنترنت الهاتف نفسه (مع DoH ومرايا).
2. **تجزئة** — تجزئة TLS لتجاوز ترشيح SNI.
3. **خوادم محفوظة** — من خوادم سليمة وُجدت سابقًا.
4. **وكيل** — وكيل SOCKS/HTTP خاص بك.
5. **thefeed** — قنوات تلغرام عبر DNS.
6. **نفق DNS** — Soar / MasterDNS / Cotten / StormDNS.

## 🧩 نفق DNS والمحركات
عندما يعمل DNS فقط دون بقية الإنترنت، تُنقل البيانات **داخل استعلامات DNS**. أربعة محركات: **MasterDNS، StormDNS، CottenDNS (وCottenMax)، Soar**. تُدخل **ملف خادمك** (لا خوادم داخل التطبيق)، عدة خوادم، اختيار خادم، و**VPN عبر النفق**.

## 🧭 المحوِّلات (Resolvers)
**بنك كبير جاهز** + **باحث عن محوّل سليم** + **اكتشاف محوّلات جديدة** من نطاقات IP محلية؛ يتحقق المحرك منها قبل الاستخدام.

## 📡 thefeed
قراءة **قنوات تلغرام عبر DNS**: قائمة القنوات والرسائل، **جلب الصور والملفات**، **قراءة QR**، وروابط/بروكسيات قابلة للنقر. (تُدخل خادم thefeed بنفسك.)

## 🔌 OpenVPN
خوادم OpenVPN العامة وملفات `.ovpn` مع **اختبار مصافحة فعلي**.

## 📤 المشاركة
إرسال الإعدادات إلى هاتف آخر (**QR/ملف/نص/رمز**) واستقبالها، **إرسال التطبيق نفسه دون إنترنت**، كشف تلقائي من الحافظة، تحديث عبر أي مسار مفتوح.

## 🎨 أخرى
خمس لغات · سمات داكنة/فاتحة/تلقائية · سجلات كاملة.

## 🔒 الخصوصية
لا يحتوي التطبيق على أي خادم أو نطاق أو مفتاح من المطوّر؛ تُدخل الملفات بنفسك وتبقى على هاتفك فقط. لا تُرسَل أي بيانات للمستخدم.

## 🔒 الشيفرة
الشيفرة المصدرية خاصة وغير منشورة.

## 📜 التراخيص
بُني ببرمجيات مفتوحة المصدر؛ انظر [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

</div>

---

## 中文

# 🌐 VPN Scan — 查找、测试并连接可用的 V2Ray 服务器

一款安卓应用，用于查找、**真实测试**并连接可用的 V2Ray 服务器；专为高度受限的网络打造，从自由互联网到封闭的国家内网。应用内不含任何服务器，由它自己从公开来源查找并测试配置。

## ⬇️ 下载
从 **Releases** 获取最新版本：
- `VPN-Scan-universal.apk` — **不清楚自己的手机就下这个**（适用于所有手机）
- `VPN-Scan-arm64.apk` — 新款手机（64 位），更小
- `VPN-Scan-arm32.apk` — 旧款手机（32 位）

安卓 8 以上 · 64 位手机可用全部功能。

## 🧠 三种内核
配置会用三种内核真实运行并测试，每台服务器都会显示它适配哪个应用：
- **Xray** — 与 **v2rayNG**、**V2Box** 相同的内核
- **Xray 25** — 与 **NPV Tunnel** 相同的内核
- **sing-box** — 与 **Hiddify** 相同的内核
- **自动：** 为每台服务器自动选择最佳内核。

## 🔎 查找与测试
- 来自**多个公开来源**的免费配置，线路被封时使用镜像和**安全 DNS（DoH）**。
- 支持全部协议：**VLESS、VMess、Trojan、Shadowsocks、Hysteria2、Hysteria、TUIC、WireGuard、AnyTLS、SOCKS**。
- **真实测试（不仅是 Ping）：** 每个配置都用内核真正启动并连上互联网；测量境外/境内延迟并通过两次测试评估稳定性。
- 结果分三类：**可用 / 已测试 / 已拒绝**，并给出拒绝原因。

## 🚀 测速
扫描后对优选服务器进行**真实下载测速**；可自动（前 10 个）或手动。

## 🌐 可达性测试（Telegram / Instagram / YouTube / Google）
每台服务器都有 **Telegram、Instagram、YouTube、Google** 按钮，立即测试该服务是否能通过它打开。

## 📶 运营商与网络信息
**IP、运营商**（自动识别或手选）、**位置、ISP、境外/境内延迟、下载速度**，并按运营商分别记录历史与设置。

## ☁ Cloudflare 优选 IP
对于域名/IP 被封的 CDN 配置，会从大型 IP 库中找到一个**干净的 Cloudflare IP** 并替换。

## ✂ 分片（Fragment）
拆分首个 **TLS** 包，使 DPI 无法通过 SNI 识别服务器；可调。

## ⭐ 收藏服务器
将好服务器加星，置顶、定期复测并在连接时优先尝试。

## 🛡 内置 VPN
一键连接最佳服务器、断线**自动切换**、**自动重连**、**Kill Switch**；**VPN** 或 **SOCKS/HTTP 代理**模式、**局域网**共享、快捷设置磁贴、通知栏实时流量统计。

## 🧭 路由与数据
**本地直连**（本地站点/IP + 自定义列表）、**分应用代理**（仅/排除所选应用）、**局域网访问**、带上限提醒的**流量管理**。

## 👤 配置档
多个独立配置档（家庭、移动…）；各自保存上网模式、运营商、扫描设置、分片、优选 IP、本地站点、应用与连接设置。

## 🔒 安全与保护
**Kill Switch**、**自动重连**（先收藏后最快）、**系统级锁定**（始终开启 VPN + 阻止无 VPN 连接）、**电池优化**。

## ⚙ 连接设置
隧道类型、内核、**MTU**、**Mux**、**分片**、**VPN 内 QUIC**、**隧道内 IPv6**（默认关闭）、日志级别。

## 🔎 扫描设置
扫描模式（**快速/均衡/完整**）、IP 版本、**自动测速**、**自动扫描**（每 3/6/12 小时）、服务器数量。

## 🛰 国家内网（国际互联网被切断时）
按顺序尝试以下路径（均可开关并重新排序）：
1. **直连** — 来自手机自身网络（含 DoH 与镜像）。
2. **分片** — 拆分 TLS 以绕过 SNI 过滤。
3. **已保存服务器** — 来自此前找到的可用服务器。
4. **代理** — 你自己的 SOCKS/HTTP 代理。
5. **thefeed** — 通过 DNS 的 Telegram 频道。
6. **DNS 隧道** — Soar / MasterDNS / Cotten / StormDNS。

## 🧩 DNS 隧道与引擎
当只有 DNS 可用而其余互联网不可用时，数据**在 DNS 查询内**传输。四个引擎：**MasterDNS、StormDNS、CottenDNS（及 CottenMax）、Soar**。你填入**自己的服务器配置**（应用内不含服务器），可保存多台、选择其一，并开启**经隧道的 VPN**。

## 🧭 解析器（Resolvers）
**大型内置解析器库** + **可用解析器查找** + 从本地 IP 段**发现新解析器**；引擎在使用前先验证。

## 📡 thefeed
通过 **DNS 读取 Telegram 频道**：频道与消息列表、**获取图片和文件**、**二维码识别**、可点击的链接/代理。（thefeed 服务器也由你填入。）

## 🔌 OpenVPN
支持公开 OpenVPN 服务器与 `.ovpn` 文件，并进行**真实握手测试**。

## 📤 分享
将配置发送到另一部手机（**二维码/文件/文本/代码**）并接收、**离线分享应用本身**、从剪贴板自动识别、通过任意可用路径更新。

## 🎨 其他
五种语言 · 深色/浅色/自动主题 · 完整日志。

## 🔒 隐私
应用不含作者的任何服务器、域名或密钥；配置由你自己填写，仅保存在你的手机上。不会向任何地方发送用户数据。

## 🔒 源代码
源代码为私有，不公开发布。

## 📜 许可
使用了开源软件；参见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。

---

## Русский

# 🌐 VPN Scan — поиск, проверка и подключение к рабочим серверам V2Ray

Приложение для Android, которое находит, **реально проверяет** и подключается к рабочим серверам V2Ray; создано для сильно ограниченных сетей — от свободного интернета до закрытой национальной сети. В приложении нет серверов; оно само находит и проверяет конфигурации из открытых источников.

## ⬇️ Загрузка
Возьмите последнюю сборку в **Releases**:
- `VPN-Scan-universal.apk` — **если не знаете свой телефон, берите этот** (работает на всех телефонах)
- `VPN-Scan-arm64.apk` — новые телефоны (64-бит), меньше
- `VPN-Scan-arm32.apk` — старые телефоны (32-бит)

Android 8+ · 64-битные телефоны для всех функций.

## 🧠 Три ядра
Конфигурации реально запускаются и проверяются тремя ядрами, и для каждого сервера показано, с каким приложением он работает:
- **Xray** — то же ядро, что у **v2rayNG** и **V2Box**
- **Xray 25** — то же ядро, что у **NPV Tunnel**
- **sing-box** — то же ядро, что у **Hiddify**
- **Авто:** выбирает лучшее ядро для каждого сервера.

## 🔎 Поиск и проверка
- Бесплатные конфигурации из **многих открытых источников**, с зеркалами и **защищённым DNS (DoH)**, когда путь заблокирован.
- Все протоколы: **VLESS, VMess, Trojan, Shadowsocks, Hysteria2, Hysteria, TUIC, WireGuard, AnyTLS, SOCKS**.
- **Реальная проверка (не только ping):** каждая конфигурация действительно запускается ядром и выходит в интернет; измеряются пинг (внешний/внутренний) и стабильность (два теста).
- Результаты в трёх группах: **рабочие / проверенные / отклонённые** с причиной.

## 🚀 Тест скорости
После сканирования лучшие серверы проходят **реальный тест скорости загрузки**; автоматически (первые 10) или вручную.

## 🌐 Тест доступности (Telegram / Instagram / YouTube / Google)
У каждого сервера есть кнопки **Telegram, Instagram, YouTube, Google**, чтобы сразу проверить, открывается ли сервис через него.

## 📶 Оператор и сеть
**IP, оператор** (авто-определение или выбор), **местоположение, ISP, пинг внешний/внутренний, скорость загрузки**, с отдельной историей и настройками по операторам.

## ☁ Чистый IP Cloudflare
Для CDN-конфигураций с заблокированным доменом/IP находится и подставляется **чистый IP Cloudflare** из большого банка.

## ✂ Фрагментация
Первый пакет **TLS** разбивается, чтобы DPI не распознал сервер по SNI; настраивается.

## ⭐ Избранные серверы
Отметьте серверы звездой — они держатся вверху, периодически перепроверяются и пробуются первыми при подключении.

## 🛡 Встроенный VPN
Подключение одним касанием к лучшему серверу, **авто-переключение** при обрыве, **авто-переподключение**, **kill switch**; режим **VPN** или **прокси SOCKS/HTTP**, раздача по **локальной сети**, плитка быстрых настроек, статистика трафика в уведомлении.

## 🧭 Маршрутизация и данные
**Локальный обход** (локальные сайты/IP + ваш список), **раздельное туннелирование** (только/кроме выбранных приложений), **доступ по локальной сети**, **управление трафиком** с оповещением о лимите.

## 👤 Профили
Несколько отдельных профилей (дом, мобильный…); каждый хранит свой режим сети, оператора, настройки сканирования, фрагмент, чистые IP, локальные сайты, приложения и настройки подключения.

## 🔒 Безопасность и защита
**Kill switch**, **авто-переподключение** (сначала избранные, потом самые быстрые), **блокировка на уровне телефона** (постоянный VPN + запрет соединений без VPN), **оптимизация батареи**.

## ⚙ Настройки подключения
Тип туннеля, ядро, **MTU**, **Mux**, **фрагмент**, **QUIC внутри VPN**, **IPv6 внутри туннеля** (по умолчанию выключено), уровень логов.

## 🔎 Настройки сканирования
Режим (**быстрый/сбалансированный/полный**), версия IP, **авто-тест скорости**, **авто-сканирование** (каждые 3/6/12 ч), число серверов.

## 🛰 Национальная сеть (когда международный интернет отключён)
Пробует эти пути по порядку (каждый можно включать и переставлять):
1. **Прямой** — из собственного интернета телефона (с DoH и зеркалами).
2. **Фрагмент** — разбиение TLS для обхода фильтрации по SNI.
3. **Сохранённые серверы** — из ранее найденных рабочих.
4. **Прокси** — ваш собственный SOCKS/HTTP-прокси.
5. **thefeed** — каналы Telegram через DNS.
6. **DNS-туннель** — Soar / MasterDNS / Cotten / StormDNS.

## 🧩 DNS-туннель и движки
Когда работает только DNS, данные передаются **внутри DNS-запросов**. Четыре движка: **MasterDNS, StormDNS, CottenDNS (и CottenMax), Soar**. Вы вводите **профиль своего сервера** (в приложении нет серверов), храните несколько, выбираете один и включаете **VPN через туннель**.

## 🧭 Резолверы
**Большой встроенный банк** + **поиск рабочего резолвера** + **обнаружение новых** из локальных диапазонов IP; движок проверяет их перед использованием.

## 📡 thefeed
Чтение **каналов Telegram через DNS**: список каналов и сообщений, **загрузка изображений и файлов**, **чтение QR**, кликабельные ссылки/прокси. (Сервер thefeed вы вводите сами.)

## 🔌 OpenVPN
Публичные серверы OpenVPN и файлы `.ovpn` с **реальной проверкой рукопожатия**.

## 📤 Обмен
Отправка конфигураций на другой телефон (**QR/файл/текст/код**) и приём, **передача самого приложения офлайн**, авто-определение из буфера обмена, обновление по любому открытому пути.

## 🎨 Прочее
Пять языков · тёмная/светлая/авто тема · полные логи.

## 🔒 Конфиденциальность
Приложение не содержит серверов, доменов или ключей от автора; профили вы вводите сами, и они остаются только на вашем телефоне. Никакие данные пользователя никуда не отправляются.

## 🔒 Исходный код
Исходный код закрыт и не публикуется.

## 📜 Лицензии
Создано с использованием ПО с открытым кодом; см. [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
