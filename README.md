

# VPN Scan

**Made by (R.S)**

جمع‌آوری و تست واقعی کانفیگ‌های V2Ray با هستهٔ خود برنامه‌ها — برای v2rayNG، V2Box، Hiddify و NPV Tunnel

[فارسی](#فارسی) · [English](#english)

[![Download APK](https://img.shields.io/badge/Download-VPN--Scan.apk-1f5eff?style=for-the-badge)](../../releases/latest/download/VPN-Scan.apk)

</div>

<table>
<tr>
<td><img src="screenshots/vs-01-home.png" width="200"></td>
<td><img src="screenshots/vs-03-results.png" width="200"></td>
<td><img src="screenshots/vs-04-server-list.png" width="200"></td>
<td><img src="screenshots/vs-12-light-results.png" width="200"></td>
</tr>
</table>

---

<div dir="rtl" id="فارسی">

## فارسی

### فهرست

- [معرفی](#معرفی)
- [امکانات](#امکانات)
- [سه هسته، چهار برنامه](#سه-هسته-چهار-برنامه)
- [نصب و شروع](#نصب-و-شروع)
- [تست چطور انجام می‌شود](#تست-چطور-انجام-میشود)
- [تنظیمات](#تنظیمات)
- [خروجی ساب](#خروجی-ساب)
- [فرگمنت TLS](#فرگمنت-tls)
- [IP تمیز کلودفلر](#ip-تمیز-کلودفلر)
- [کانفیگ‌های دستی و نت ملی](#کانفیگهای-دستی-و-نت-ملی)
- [لاگ برنامه و دلیل ردها](#لاگ-برنامه-و-دلیل-ردها)
- [مجوزها و حریم خصوصی](#مجوزها-و-حریم-خصوصی)
- [سؤال‌های رایج](#سؤالهای-رایج)
- [اعتبارها و مجوز کتابخانه‌ها](#اعتبارها-و-مجوز-کتابخانهها)

### معرفی

**VPN Scan** کانفیگ‌های رایگان V2Ray را از بیش از ۱۰۰ منبع جمع می‌کند (گیت‌هاب، سایت‌ها، کانال‌های تلگرام و منابع داخلی). بعد هر کانفیگ را با **هستهٔ واقعی** همان برنامه‌ای که استفاده می‌کنی تست می‌کند و فقط سرورهایی را نشان می‌دهد که واقعاً وصل می‌شوند. سرورهای سالم با یک دکمه به **v2rayNG**، **V2Box**، **Hiddify** یا **NPV Tunnel** فرستاده می‌شوند.

### امکانات

**🧪 تست واقعی با سه هسته**
- هر کانفیگ با هستهٔ همان برنامه تست می‌شود؛ پینگ ساده نیست، دو درخواست واقعی از داخل خود کانفیگ فرستاده می‌شود.
- یکی، چند تا یا هر سه هسته را می‌شود انتخاب کرد.
- زیر هر سرور معلوم است با کدام برنامه سالم بوده: ✓ سالم، خط‌خورده = وصل نشد، «—» = آن هسته این نوع کانفیگ را پشتیبانی نمی‌کند.

**➕ افزودن به برنامه‌ها**
- چهار دکمه: v2rayNG، V2Box، Hiddify، NPV Tunnel؛ تعداد سرورهای سالم هر برنامه روی دکمه‌اش نوشته شده.
- هر دکمه فقط سرورهایی را می‌فرستد که با هستهٔ همان برنامه سالم بوده‌اند.
- v2rayNG کانفیگ‌ها را مستقیم می‌گیرد؛ برای بقیه لینک‌ها کپی می‌شوند و برنامه باز می‌شود («افزودن از کلیپ‌بورد»).

**🏷 اسم و پرچم**
- سرورهای سالم به ترتیب سرعت «R.S 1»، «R.S 2»، … نام می‌گیرند و پرچم کشورشان کنار اسم می‌آید (🇩🇪 R.S 1). اسم و پرچم داخل خود لینک هم می‌رود، پس در برنامهٔ VPN هم دیده می‌شود.
- کشور از روی IP و با یک بانک داخل برنامه پیدا می‌شود (روی نت ملی هم کار می‌کند). سرورهای پشت CDN علامت ☁️ می‌گیرند.

**🌍 تست باز شدن سایت‌ها**
- برای هر سرور سالم بررسی می‌شود که گوگل، یوتیوب، اینستاگرام و تلگرام از داخلش باز می‌شوند یا نه.
- فیلتر «فقط سرورهایی که باز می‌کنند» لیست، دکمه‌ها و ساب را محدود می‌کند.

**📦 خروجی ساب** · **✂️ فرگمنت TLS** · **🧹 IP تمیز کلودفلر** · **📝 کانفیگ دستی** — توضیح کامل هر کدام پایین‌تر آمده.

**📡 وضعیت اینترنت و حالت‌ها**
- IP، اپراتور، موقعیت، ISP، پینگ خارج و داخل و سرعت دانلود نشان داده می‌شود.
- حالت اسکن: **خودکار** (از روی وضعیت نت)، **نت ملی** (فقط سرورهای داخل ایران و منابع داخلی)، **اینترنت ضعیف** (تست صبورتر)، **اینترنت خوب** (سریع، همهٔ منابع).
- اپراتور (همراه اول، ایرانسل، مخابرات، آپتل، سامانتل، شاتل) خودکار تشخیص داده می‌شود یا دستی انتخاب می‌شود.

**🌐 پروتکل‌ها**
VLESS (با REALITY و Vision) · VMess · Trojan · Shadowsocks · Hysteria2 · Hysteria · TUIC · AnyTLS · WireGuard · SOCKS
ترابری‌ها: TCP، WebSocket، gRPC، HTTP/2، HTTPUpgrade، XHTTP، mKCP

**و بیشتر**
- تست دوبارهٔ سالم‌ها و حذف سرورهای قطع‌شده
- QR کد، کپی، اشتراک‌گذاری، فایل TXT و فایل ساب
- لاگ برنامه با دلیل رد شدن کانفیگ‌ها، جدا برای هر هسته
- به‌روزرسانی از داخل برنامه با نوار پیشرفت
- فارسی و English · تم تیره، روشن (آبی کم‌رنگ) یا خودکار هم‌رنگ گوشی

### سه هسته، چهار برنامه

| هسته | نسخه | برنامه | نکته |
|---|---|---|---|
| Xray | 26.10.21 | v2rayNG · V2Box | هستهٔ جدید؛ VLESS/Trojan بدون TLS را قبول نمی‌کند. TUIC، Hysteria و AnyTLS ندارد |
| Xray | 25.10.15 | NPV Tunnel | همان نسخهٔ NPV؛ بدون TLS و allowInsecure را قبول می‌کند |
| sing-box | 1.14.4 | Hiddify | TUIC، Hysteria و AnyTLS دارد؛ XHTTP و mKCP ندارد |

> هستهٔ Xray 26 داخل کتابخانهٔ برنامه است. Xray 25 و sing-box فایل اجرایی جدا هستند و **فقط روی گوشی‌های ۶۴ بیتی** (arm64) کار می‌کنند؛ روی گوشی ۳۲ بیتی فقط Xray 26 تست می‌کند. با «همه» هر کانفیگ با سه هسته تست می‌شود و اسکن کندتر است؛ برای سرعت بیشتر فقط هستهٔ برنامهٔ خودت را انتخاب کن.

### نصب و شروع

1. فایل [VPN-Scan.apk](../../releases/latest/download/VPN-Scan.apk) را دانلود کن، نصب از منابع ناشناس را اجازه بده و نصبش کن (اندروید ۸ به بالا).
2. صبر کن وضعیت اینترنت مشخص شود. حالت را روی «خودکار» بگذار یا خودت انتخاب کن.
3. پروتکل‌ها و هسته‌ها را انتخاب کن.
4. **شروع اسکن V2Ray** را بزن. سرورهای سالم کم‌کم در لیست می‌آیند.
5. در پایان، دکمهٔ برنامه‌ات را بزن (مثلاً «➕ Hiddify») یا از «📦 خروجی ساب» یک لینک ساب بساز.

### تست چطور انجام می‌شود

1. **جمع‌آوری:** همهٔ منابع خوانده می‌شوند. از هر فایل فقط بخش اول (تازه‌ترین‌ها، حدود ۴۰۰ کیلوبایت) گرفته می‌شود تا حجم اینترنت کم مصرف شود. کانفیگ‌ها نوبتی از همهٔ منابع برداشته می‌شوند (منابع ایران جلوتر) و تکراری‌ها حذف می‌شوند؛ حداکثر ۱۲۰۰۰ کانفیگ.
2. **فیلتر:** فقط پروتکل‌ها و هسته‌های انتخاب‌شده. کانفیگی که هیچ هستهٔ انتخاب‌شده‌ای اجرایش نمی‌کند، تست نمی‌شود.
3. **DNS و پینگ TCP:** دامنه با DNS گوشی به IP تبدیل می‌شود و با یک اتصال TCP سریع، سرورهای خاموش کنار می‌روند. در نت ملی فقط IPهای داخل ایران می‌مانند.
4. **تست واقعی:** با هر هستهٔ انتخاب‌شده دو درخواست واقعی از داخل کانفیگ (gstatic و google) فرستاده می‌شود. اگر هر دو جواب بدهند و میانگین تأخیر زیر حد انتخابی باشد، سرور برای آن برنامه سالم است.
5. **گواهی:** برای کانفیگ‌های TLS «ناامن» (insecure)، گواهی سرور گرفته و پین می‌شود (مثل v2rayNG جدید)؛ لینک خروجی هم همان پین را دارد.
6. **IP تمیز:** کانفیگ‌های کلودفلر که با IP خودشان وصل نشدند، با یک IP تمیز دوباره تست می‌شوند.
7. **فرگمنت:** کانفیگ‌هایی که در دست‌دادن TLS قطع شدند، یک بار هم با فرگمنت تست می‌شوند.
8. **سایت‌ها:** برای سرورهای سالم باز شدن گوگل، یوتیوب، اینستاگرام و تلگرام بررسی می‌شود.

### تنظیمات

| تنظیم | گزینه‌ها | پیش‌فرض |
|---|---|---|
| تعداد سرور سالم | ۱۰ · ۳۰ · ۵۰ · ۱۰۰ | ۳۰ |
| حداکثر تأخیر واقعی | زیر ۵۰۰ · ۱۰۰۰ · ۲۰۰۰ · ۳۰۰۰ · ۵۰۰۰ میلی‌ثانیه | زیر ۲۰۰۰ |
| تست هم‌زمان | ۴ · ۸ · ۱۲ · ۱۶ (گوشی ضعیف: کمتر) | ۸ |
| پینگ سریع TCP | کنار گذاشتن سرورهای خاموش پیش از تست هسته | روشن |
| منابع عمومی | گرفتن از منابع گیت‌هاب، سایت‌ها و کانال‌ها | روشن |
| ✂ فرگمنت TLS | تست دوباره با فرگمنت | روشن |
| 🌍 تست سایت‌ها | گوگل، یوتیوب، اینستاگرام، تلگرام | روشن |
| پروتکل‌ها / هسته‌ها | هر کدام یا «همه» | همه |
| حالت / اپراتور | خودکار یا دستی | خودکار |

دکمهٔ **↺ بازگشت به تنظیمات پیش‌فرض** همه را به جدول بالا برمی‌گرداند.

### خروجی ساب

دکمهٔ **📦 خروجی ساب** همهٔ سالم‌ها را برای هر برنامه جدا نشان می‌دهد (v2rayNG · V2Box، Hiddify، NPV Tunnel):
- **کپی ساب (Base64)**، **کپی لینک‌ها** و **ذخیرهٔ فایل ساب** — همیشه کار می‌کنند.
- **لینک ساب داخلی** (`http://127.0.0.1:18920/ng`، `/hid`، `/npv`): یک بار در برنامهٔ VPN اضافه‌اش کن؛ از آن به بعد با «به‌روزرسانی ساب» آخرین سالم‌های اسکن می‌آیند. برای v2rayNG و Hiddify با یک دکمه اضافه می‌شود. این لینک فقط روی خود گوشی و فقط وقتی VPN Scan باز است کار می‌کند.

### فرگمنت TLS

فیلترینگ هوشمند معمولاً از روی اولین بستهٔ دست‌دادن TLS (ClientHello) سرور را تشخیص می‌دهد. فرگمنت این بسته را تکه‌تکه می‌فرستد. سرورهایی که فقط با فرگمنت سالم شدند، علامت **✂** می‌گیرند. برای استفاده، فرگمنت را در برنامهٔ VPN روشن کن:

```
packets: tlshello · length: 10-20 · interval: 10-20
```

در v2rayNG: تنظیمات ← Fragment · در Hiddify: تنظیمات ← TLS Tricks ← Fragment · در NPV: تنظیمات Fragment.

### IP تمیز کلودفلر

خیلی از کانفیگ‌ها پشت کلودفلر هستند و IP خودشان روی اینترنت ایران فیلتر است. برنامه این کانفیگ‌ها را با یک IP تمیز کلودفلر دوباره تست می‌کند و اگر سالم شدند، IP تمیز را در لینکشان می‌گذارد (دامنه به‌عنوان SNI و Host می‌ماند).
- IP تمیز را خود برنامه پیدا می‌کند (تست TLS واقعی روی کلودفلر).
- لیست خودت را هم می‌توانی بدهی: چسباندن متن یا فایل TXT؛ هر خط یک IP یا رنج مثل `104.17.0.0/24`.

### کانفیگ‌های دستی و نت ملی

در بخش **📝 کانفیگ‌های دستی و منابع خودت** می‌توانی:
- یک یا چند کانفیگ (`vless://`، `vmess://`، `trojan://`، `ss://`، `hy2://`، `tuic://`، …)، لینک ساب یا کانال داخلی (`eitaa:اسم‌کانال`، `bale:اسم‌کانال`) را بچسبانی یا فایل TXT بدهی.
- با **🧪 فقط همین‌ها را تست کن** فقط همان‌ها را با همهٔ امکانات تست کنی.
- انتخاب کنی در اسکن معمولی هم همراه بقیه تست شوند.

در **نت ملی**: منابع خارجی باز نمی‌شوند؛ برنامه از منابع داخلی، کانفیگ‌های ذخیره‌شده از اسکن‌های قبلی (تا ۴۰۰۰ کانفیگ) و کانفیگ‌های دستی استفاده می‌کند و فقط سرورهای داخل ایران را نگه می‌دارد. یک بار با اینترنت آزاد اسکن کن تا این ذخیره پر شود.

### لاگ برنامه و دلیل ردها

از منو ← **📋 لاگ برنامه** همهٔ رویدادها دیده می‌شود (کپی و اشتراک‌گذاری هم دارد). در پایان هر اسکن دلیل ردها، جدا برای هر هسته، نوشته می‌شود:

| دلیل | معنی |
|---|---|
| پینگ TCP جواب نداد | سرور خاموش است یا IP روی اپراتور تو فیلتر است |
| دامنه پیدا نشد | دامنه وجود ندارد یا فیلتر است |
| تست واقعی ناموفق | وصل نشد؛ مثل `closed pipe` (کانفیگ از کار افتاده) یا `tls handshake timeout` (فیلترینگ) |
| تست دوم ناموفق | فقط یک بار جواب داد؛ ناپایدار |
| بدون TLS | هستهٔ جدید Xray (و v2rayNG جدید) قبول نمی‌کند؛ با NPV و Hiddify تست می‌شود |
| گواهی سرور گرفته نشد | برای پین کردن گواهی جواب نداد |
| کانفیگ در هسته بالا نیامد | کانفیگ خراب است یا آن هسته قبولش نمی‌کند |
| کندتر از حد | سالم، ولی تأخیرش از حد انتخابی بیشتر است |
| سالم با IP تمیز / سالم با فرگمنت | فقط با IP تمیز یا فرگمنت سالم شد |


### مجوزها و حریم خصوصی

- `INTERNET`: دریافت منابع و تست سرورها.
- `REQUEST_INSTALL_PACKAGES`: فقط برای نصب نسخهٔ جدید از داخل برنامه.
- برنامه هیچ اطلاعاتی برای سازنده نمی‌فرستد. برای وضعیت اینترنت از `ipwho.is` / `ipapi.co` و برای سرعت از `speed.cloudflare.com` استفاده می‌شود. تنظیمات، نتیجه‌ها و لاگ فقط روی گوشی ذخیره می‌شوند.
- سرور ساب داخلی فقط روی `127.0.0.1` باز است و از بیرون گوشی در دسترس نیست
- کانفیگ‌ها مال افراد دیگرند؛ اطلاعات حساس را با احتیاط بفرست.

### سؤال‌های رایج

**از هزار کانفیگ فقط چند تا سالم است؟** طبیعی است؛ بیشتر کانفیگ‌های عمومی یا مرده‌اند یا روی اینترنت ایران فیلترند. لاگ برنامه دقیقاً دلیل را می‌گوید. فرگمنت و IP تمیز را روشن نگه دار و حالت را درست انتخاب کن.

**چرا یک سرور با v2rayNG سالم است و با Hiddify نه (یا برعکس)؟** هسته‌ها با هم فرق دارند (جدول بالا). برای همین هر دکمه فقط سالم‌های هستهٔ خودش را می‌فرستد.

**هستهٔ NPV یا Hiddify اجرا نشد؟** گوشی ۳۲ بیتی است؛ این دو هسته فقط روی ۶۴ بیتی هستند. لاگ دلیل دقیق را می‌نویسد.

**در برنامهٔ VPN وصل نمی‌شود ولی اینجا سالم بود؟** کانفیگ‌های عمومی زود از کار می‌افتند؛ «تست دوباره» بزن. اگر علامت ✂ دارد، فرگمنت را در برنامه‌ات روشن کن.

**آیفون؟** این برنامه فقط اندروید است.

### اعتبارها و مجوز کتابخانه‌ها

- [Xray-core](https://github.com/XTLS/Xray-core) (MPL-2.0) و [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite)
- [sing-box](https://github.com/SagerNet/sing-box) (GPL-3.0) — فایل اجرایی رسمی بدون تغییر؛ سورس در همان مخزن
- داده‌های کشور: GeoLite2 از MaxMind (CC BY-SA 4.0) از طریق فهرست geoip پروژهٔ v2fly
- QR Code for JavaScript از Kazuhiko Arase (MIT)

</div>

---

<div id="english">

## English

**VPN Scan** collects free V2Ray configs from 100+ sources (GitHub, websites, Telegram channels and domestic sources), tests every config with the **real core** of the app you use, and shows only servers that actually connect. Working servers go to **v2rayNG**, **V2Box**, **Hiddify** or **NPV Tunnel** with one tap.

### Features

- **Real tests with three cores.** Each config is tested with the core of each app — two real requests through the config, not just a ping. Pick one core, several, or all. Each server shows which apps it works in (✓ works, struck through = failed, "—" = unsupported by that core).
- **Add to your app.** Four buttons with per-app counts. Each sends only the servers that passed that app's core. v2rayNG imports directly; for the others the links are copied and the app opens ("Add from clipboard").
- **Names and flags.** Working servers are named R.S 1, R.S 2, … by speed, with the server's country flag (🇩🇪 R.S 1), also inside the link itself. Country comes from a bundled IP database (works on the national internet); CDN servers get ☁️.
- **Site access test.** Google, YouTube, Instagram and Telegram are checked through each working server; a filter limits the list, buttons and subscription to servers that open the sites you need.
- **Subscription export, TLS fragment, clean Cloudflare IPs, manual configs** — see below.
- **Network status and modes.** IP, operator, location, ISP, ping and download speed. Scan modes: Auto, National internet (Iranian servers and domestic sources only), Weak internet (more patient), Good internet (fast, all sources). Operator auto-detected or chosen manually.
- **Protocols:** VLESS (REALITY, Vision), VMess, Trojan, Shadowsocks, Hysteria2, Hysteria, TUIC, AnyTLS, WireGuard, SOCKS. Transports: TCP, WebSocket, gRPC, HTTP/2, HTTPUpgrade, XHTTP, mKCP.
- Retest working servers, QR codes, copy, share, TXT and subscription files, app log with reject reasons per core, in-app updates, Persian and English, dark / light (pale blue) / automatic theme.

### Cores

| Core | Version | App | Notes |
|---|---|---|---|
| Xray | 26.10.21 | v2rayNG · V2Box | Rejects VLESS/Trojan without TLS; no TUIC, Hysteria, AnyTLS |
| Xray | 25.10.15 | NPV Tunnel | Same version as NPV; accepts no-TLS and allowInsecure |
| sing-box | 1.14.4 | Hiddify | Has TUIC, Hysteria, AnyTLS; no XHTTP or mKCP |

Xray 26 is built into the app library. Xray 25 and sing-box are separate executables and run **on 64-bit (arm64) phones only**; on 32-bit phones only Xray 26 is tested. Testing with all cores is slower; select just your app's core for a faster scan.

### Getting started

1. Download [VPN-Scan.apk](../../releases/latest/download/VPN-Scan.apk), allow unknown sources and install (Android 8+).
2. Wait for the network status. Leave the mode on Auto or pick one.
3. Choose protocols and cores, then tap **Start V2Ray scan**.
4. Tap your app's button (e.g. "➕ Hiddify") or create a subscription from "📦 Subscription export".

### How testing works

1. **Collect:** every source is read; only the first ~400 KB (newest configs) of each file. Configs are taken round-robin from all sources (Iranian first), de-duplicated, up to 12,000.
2. **Filter:** only selected protocols, and only configs at least one selected core can run.
3. **DNS and TCP ping:** the phone's DNS resolves the address and a quick TCP connect drops dead servers. In national mode only Iranian IPs are kept.
4. **Real test:** for each selected core, two real requests (gstatic and google) go through the config. Both must answer and the average delay must be under your limit.
5. **Certificates:** for "insecure" TLS configs the server certificate is fetched and pinned (like recent v2rayNG); exported links carry the pin.
6. **Clean IP:** Cloudflare configs that fail on their own IP are retried through a clean IP.
7. **Fragment:** configs that fail the TLS handshake are retried with fragmentation.
8. **Sites:** working servers are checked for Google, YouTube, Instagram and Telegram.

### Settings

| Setting | Options | Default |
|---|---|---|
| Working servers to find | 10 · 30 · 50 · 100 | 30 |
| Max real delay | under 500 · 1000 · 2000 · 3000 · 5000 ms | under 2000 |
| Concurrent tests | 4 · 8 · 12 · 16 | 8 |
| Fast TCP ping | skip dead servers before core tests | on |
| Public sources | GitHub, websites, channels | on |
| ✂ TLS fragment | retest with fragmentation | on |
| 🌍 Site test | Google, YouTube, Instagram, Telegram | on |
| Protocols / cores | any or All | All |
| Mode / operator | auto or manual | auto |

**↺ Reset to defaults** restores the table above.

### Subscription export

"📦 Subscription export" groups working servers per app (v2rayNG · V2Box, Hiddify, NPV Tunnel):
- **Copy subscription (Base64)**, **copy links** and **save subscription file** always work.
- **Local subscription link** (`http://127.0.0.1:18920/ng`, `/hid`, `/npv`): add it once to your VPN app; "Update subscription" then pulls the latest working servers. One-tap add for v2rayNG and Hiddify. Works only on the same phone, while VPN Scan is open.

### TLS fragment

DPI usually spots a server from the first TLS handshake packet (ClientHello); fragmentation splits it. Servers that only work with fragmentation get **✂**. Turn on fragment in your VPN app with:

```
packets: tlshello · length: 10-20 · interval: 10-20
```

### Clean Cloudflare IPs

Many configs sit behind Cloudflare and their own IP is filtered in Iran. The app retests them through a clean Cloudflare IP and, if they work, puts that IP in the link (the domain stays as SNI and Host). Clean IPs are found automatically, or you can give your own list by pasting or a TXT file (one IP or range like `104.17.0.0/24` per line).

### Manual configs and national internet

Under "📝 Manual configs & your own sources", paste one or more configs, subscription links or domestic channels (`eitaa:channel`, `bale:channel`) or load a TXT file. "🧪 Test only these" tests just them; optionally include them in normal scans.
On the national internet foreign sources don't open; the app uses domestic sources, configs saved from earlier scans (up to 4,000) and manual configs, and keeps only Iranian servers. Scan once on free internet to fill the cache.

### App log and reject reasons

Menu → "📋 App log" shows every event (copy and share included). After each scan, reject reasons are listed per core: TCP ping failed (server off or IP filtered), domain not found, real test failed (`closed pipe` = expired config, `tls handshake timeout` = filtering), second test failed (unstable), no TLS (rejected by new Xray; tested with NPV and Hiddify), certificate not fetched, config failed to load, slower than limit, working via clean IP / fragment.

### Build from source

GitHub Actions builds the APK (`.github/workflows/build.yml`): upload `vpn-scan-src.zip` (if the zip is absent, the `source/` folder is built instead — same code, unpacked so it can be read on GitHub); the workflow unpacks it, builds with Java 17 and Gradle 8.9, downloads the cores (libv2ray.aar v26.10.21, Xray v25.10.15 arm64, sing-box 1.14.4 arm64) and publishes `VPN-Scan.apk` to Releases as version `1.{run number}`. Locally: install Android SDK 34 and JDK 17 and run `gradle assembleDebug` in the source folder.

Security note: the signing key (`rs-key.jks`) and its password are in the source so updates install over the previous version. Because the repository is public, anyone can build an APK with the same signature; keep the key in GitHub Secrets if only you should publish official builds.

### Project structure

`app/build.gradle` (cores, signing, version) · `MainActivity.java` (WebView + `window.RSNative` bridge: `v2test`, `v2proc`, `v2sites`, `v2ping`, `v2resolve`, `v2cert`, `cfprobe`, `v2geo`, `subSet`/`subPort`, `v2import`, `v2cores`, `fetch`/`fetchPart`, updates, theme) · `assets/index.html` (entire UI and scan logic) · `assets/geo4.bin` (IP → country) · `res/mipmap-*` (icon).

### Permissions and privacy

`INTERNET` for sources and tests; `REQUEST_INSTALL_PACKAGES` only for in-app updates. Nothing is sent to the developer. Network status uses `ipwho.is` / `ipapi.co` and speed uses `speed.cloudflare.com`. Settings, results and logs stay on the phone. The local subscription server listens only on `127.0.0.1`. Configs are run by third parties; be careful with sensitive data.

### FAQ

- **Only a few of a thousand work?** Normal: most public configs are dead or filtered in Iran. The log tells you why. Keep fragment and clean IP on and pick the right mode.
- **Works with v2rayNG but not Hiddify?** The cores differ (see table); each button only sends servers that passed its own core.
- **NPV or Hiddify core didn't run?** The phone is 32-bit; those cores are 64-bit only.
- **Fails in the VPN app?** Public configs expire quickly — retest. If it has ✂, enable fragment in your app.
- **iPhone?** Android only.

### Credits and licenses

[Xray-core](https://github.com/XTLS/Xray-core) (MPL-2.0) and [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite) · [sing-box](https://github.com/SagerNet/sing-box) (GPL-3.0, official unmodified binary; source in its repository) · Country data: GeoLite2 by MaxMind (CC BY-SA 4.0) via the v2fly geoip list · QR Code for JavaScript by Kazuhiko Arase (MIT).

</div>

---

<div align="center">

**Made by (R.S)**

</div>
