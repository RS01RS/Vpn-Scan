<div dir="rtl">

# 🌐 VPN Scan — یابنده و تست‌کنندهٔ سرورهای V2Ray با VPN داخلی

**Made by (R.S)** · برنامهٔ اندروید برای پیدا کردن، تست واقعی و وصل شدن به سرورهای سالم V2Ray، مخصوص شرایط اینترنت ایران؛ از اینترنت آزاد تا نت ملی.

## ⬇️ دانلود
آخرین نسخه را از بخش **[Releases](../../releases/latest)** بگیر (فایل `VPN-Scan.apk`) و نصب کن.
اندروید ۸ به بالا · گوشی‌های ۶۴ بیتی (arm64) برای همهٔ امکانات.

## ✨ امکانات

### 🔎 پیدا کردن و تست
- کانفیگ‌های رایگان از **۲۰۰ منبع** (گیت‌هاب و کانال‌های تلگرام) با آینه‌ها و DNS امن (DoH) وقتی منبعی بسته است
- همهٔ پروتکل‌ها: VLESS، VMess، Trojan، Shadowsocks، Hysteria2، Hysteria، TUIC، WireGuard، AnyTLS، SOCKS
- **تست واقعی با سه هسته:** Xray (مثل v2rayNG / V2Box)، Xray 25 (مثل NPV Tunnel) و sing-box (مثل Hiddify)؛ برای هر سرور معلوم است با کدام برنامه کار می‌کند
- تشخیص وضعیت اینترنت و اپراتور (همراه اول، ایرانسل، مخابرات و…) و سابقهٔ جدا برای هر اپراتور
- اسکن خودکار، تست سرعت خودکار ۱۰ سرور برتر، علاقه‌مندی‌ها ⭐
- یابندهٔ **IP تمیز کلودفلر** (بانک ۴۳ هزار IP) و **فرگمنت** برای دور زدن فیلتر SNI

### 🛡 VPN داخلی
- وصل شدن با یک لمس به بهترین سرور، **جابه‌جایی خودکار** وقتی سرور قطع شد، اتصال دوباره خودکار، Kill Switch
- **بای‌پس ایران** (سایت‌های داخلی مستقیم) و سایت‌های دلخواه، **Split Tunneling** (برنامه‌های انتخابی)
- حالت VPN یا پروکسی SOCKS/HTTP، اشتراک روی شبکهٔ محلی (LAN)، کاشی تنظیمات سریع، آمار ترافیک در اعلان
- تنظیمات پیشرفته: MTU، Mux، فرگمنت، فقط IPv4، سطح لاگ، پروفایل‌ها، مصرف باتری و حجم
- **OpenVPN:** سرورهای VPN Gate و فایل‌های ‎.ovpn با تست واقعی دست‌دهی

### 🛰 نت ملی (وقتی اینترنت بین‌الملل قطع است)
- مسیرهای چندگانه برای گرفتن کانفیگ: مستقیم ← فرگمنت ← سرورهای ذخیره‌شده ← پروکسی ← thefeed ← تونل DNS
- **تونل DNS** با موتورهای MasterDNS، StormDNS، CottenDNS (و CottenMax) و Soar — پروفایل سرور خودت را وارد می‌کنی (هیچ سروری داخل برنامه نیست)، انتخاب سرور، VPN از راه تونل
- **بانک ۷٬۰۸۰ resolver** + یابندهٔ resolver سالم + **کشف resolver جدید** در رنج‌های IP ایران
- **thefeed:** خواندن کانال‌های تلگرام از راه DNS، نمایش کانال‌ها و پیام‌ها، دریافت عکس و فایل، **خواندن QR** داخل عکس‌ها
- کانفیگ از رکورد TXT دامنه، آینهٔ داخلی، منابع داخلی (بله، ایتا، روبیکا)
- دو انبار ۱۰۰۰تایی: آخرین کانفیگ‌های سالم و کانفیگ‌هایی که در نت ملی جواب داده‌اند

### 📤 اشتراک
- ارسال کانفیگ‌ها به گوشی دیگر (صفحه‌های QR، فایل، کد VPNSCAN، متن) و دریافت از دوست
- **ارسال خود برنامه بدون اینترنت** (Quick Share، بلوتوث…)
- تشخیص خودکار کانفیگ از کلیپ‌بورد و «اشتراک‌گذاری» از تلگرام
- بررسی و دانلود نسخهٔ جدید از هر مسیری که باز باشد

### 🎨 دیگر
- فارسی و انگلیسی · تم تیره، روشن و خودکار · لاگ و گزارش کامل

## 🔒 حریم خصوصی
- برنامه هیچ سرور، دامنه یا کلیدی از سازنده ندارد؛ پروفایل‌های تونل DNS و thefeed را خودت وارد می‌کنی و فقط روی گوشی خودت می‌مانند.
- هیچ اطلاعاتی از کاربر به جایی فرستاده نمی‌شود.

## 🔐 امنیت کد
- کد **جاوا** با R8 مبهم می‌شود (نام کلاس‌ها و متدها بی‌معنی می‌شوند).
- کد **جاوااسکریپت** داخل صفحه فشرده و بدون توضیحات است.
- سورس در ریپو **رمزدار** (`source.enc`) است و فقط داخل ماشین گیت‌هاب باز می‌شود؛ در لاگ‌های عمومی چیزی از کد دیده نمی‌شود.

## 🛠 ساخت (برای صاحب ریپو)
هر push دو خروجی می‌سازد و در **Releases** می‌گذارد:
- **`.apk`** — نسخهٔ github، برای دانلود و نصب مستقیم (با نصب و آپدیت داخلی).
- **`-play.aab`** — نسخهٔ گوگل پلی، برای آپلود در Play Console (بدون نصب داخلی، سازگار با قوانین پلی).

مراحل راه‌اندازی (یک‌بار):
1. **Settings → Secrets and variables → Actions → New repository secret** · اسم: `SRC_PASS` · مقدار: رمز سورس (که جدا برایت فرستاده شده).
2. **Settings → Actions → General → Workflow permissions** → «Read and write permissions».
3. هر بار `source.enc` تازه را push کنی، هر دو نسخه خودکار ساخته می‌شوند (یا از تب Actions دستی «Run workflow» بزن).

## 📱 انتشار در گوگل پلی (اختیاری)
- فایل **`-play.aab`** را در [Play Console](https://play.google.com/console) آپلود کن.
- **سیاست حریم خصوصی** لازم است: فایل [PRIVACY.md](PRIVACY.md) را به‌صورت یک صفحهٔ عمومی منتشر کن (ساده‌ترین راه: در Settings → Pages این ریپو، GitHub Pages را روشن کن) و لینکش را در Play Console بگذار.
- اگر برنامه VPN دارد، **فرم اعلام VpnService** را در Play Console پر کن و VPN را کارکرد اصلی اعلام کن.

## 💰 تبلیغات
برنامه بدون تبلیغ کامل کار می‌کند. جای تبلیغ (بنر پایین + تمام‌صفحهٔ قابل‌بستن بعد از اسکن) آماده است؛ برای فعال کردن با حساب AdMob خودت، [ADMOB_SETUP.md](ADMOB_SETUP.md) را ببین.

## 📜 مجوزها
از نرم‌افزارهای متن‌باز استفاده شده؛ فهرست و مجوزهایشان در [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

---
</div>

## English
**VPN Scan** finds, really tests and connects to working V2Ray servers (VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC, WireGuard, AnyTLS…) from 200 sources, with three cores (Xray, Xray 25, sing-box), a built-in VPN (auto-switch, kill switch, Iran bypass, split tunnelling), a Cloudflare clean-IP finder, OpenVPN, and a national-net toolkit: DNS tunnels (MasterDNS, StormDNS, CottenDNS, Soar), a 7,080-resolver bank with discovery, thefeed (Telegram channels over DNS, images, QR), TXT-record configs and domestic mirrors. Persian / English. Download the APK from **Releases**. The source code is not public (encrypted; decrypted only inside GitHub Actions).
