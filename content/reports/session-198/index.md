title: گزارش جلسه ۱۹۸ام گروه کاربران لینوکس مشهد
save_as: reports/session-198/index.html
url: reports/session-198
category: reports
date: 2017/05/16 23:18

این جلسه در روز سه‌شنبه ۲۶ اردیبهشت ماه ۱۳۹۶ با حضور اعضای گروه در محل شتاب دهنده TrigUp فناپ برگزار شد. مباحثی که در این
جلسه به آنها پرداخته شد را در زیر مشاهده خواهید نمود:
<!--more-->

## اخبار دنیای گنو/لینوکس و متن‌باز *مصطفی ستاری*
جلسه امروز با مرور اخبار مرتبط با نرم‌افزارهای متن‌باز آغاز شد. در زیر با بخشی از آن عناوین آشنا میشویم:

* انتشار نسخه OpenSSH v7.5 و پایان پشتیبانی از پروتکل SSHv1
* انتشار نسخه Wine v2.8
* پشتیبانی از اجرای فایل‌های باینری لینوکس (Linux ELF) توسط سیستم‌عامل مایکروسافت ویندوز
* پایان امتیاز اختراع انکدینگ Mp3 و ساپورت قریب‌الوقوع توزیع فدورا
* انتشار نسخه جدید سیستم‌عامل‌های Debian 8.8, pfSense v2.3.4, FreeNAS 11.0-RC, GRML 2017.5 RC1
* انتشار نسخه Ardour 5.9
* و نهایتا خبر انتشار [سیستم‌عامل جدید گوگل](https://en.wikipedia.org/wiki/Google_Fuchsia)

## بررسی چند رخنه امنیتی در ویندوز *احسان نمکی*
در ادامه، گروه میزبان آقای احسان نمکی با ارائه‌ای چالش برانگیز درباره امنیت بود. در این ارائه ابتدا به اختصار با تاریخچه‌ای از شکل گیری 
سیستم‌عامل یونیکس و نحوه شکل گیری سیستم‌عامل‌های BSD، پروژه GNU و همچنین سیستم عامل Linux آشنا شدیم. مقدمه‌ای از این
ارائه را در زیر بخوانیم:

> عبارت باگ  به نوعی اشکال یا اشتباه در اجرای نرم‌افزار که موجب نتایج اشتباه یا اجرا نشدن نرم‌افزار می‌شود، اطلاق می‌گردد. برنامه‌نویسان
مایکروسافت سابقه طولانی در این زمینه داشته‌اند و نسخه‌های مختلف ویندوز با باگ‌های کوچک و بزرگی همراه بوده که معمولاًً با ارائه
به‌روزرسانی‌های مختلف برطرف شده است اما در بعضی اوقات باگ هایی که در پرنگ ترین محصول مایکروسافت یعنی ویندوز دیده میشود
که خسارات جبران ناپذیری را به دنبال دارد  ویندوز و باگهایش بارها و بارها خسارت های شدید به صاحب کپانی های بزرگ زده است که یکی از
خدایان این باگ ها به  بانام  ممم شناخته می شود این باگ  به راحتی آب خوردن  سیستم  را در اختیار شخص هکر می گذارد.

در ادامه با معرفی توزیع کالی و توضیحی مختصر بر نحوه کار با فریم‌ورک  [Metasploit](https://en.wikipedia.org/wiki/Metasploit_Project)
به بررسی دو مورد از آسیب‌پذیری‌های جدی در سیستم عامل ویندوز به نام‌های  [MS08_067](https://technet.microsoft.com/en-us/library/security/ms08-067.aspx)
و همچنین [MS12_020](https://technet.microsoft.com/en-us/library/security/ms12-020.aspx)
در سال‌های ۲۰۰۸ و ۲۰۱۲ میلادی آشنا شدیم. درباره آسیب‌پذیر اخیر سیستم‌عامل ویندوز مرتبط با
باج افزار [WannaCry](https://en.wikipedia.org/wiki/WannaCry_ransomware_attack)
صحبت کردیم و در انتهای ارائه نیز، سوالات زیادی از سمت اعضای حاضر در جلسه مطرح و پاسخ آن با دیگر اعضای گروه به اشتراک گذاشته شد.

## بحث آزاد
در انتهای جلسه طبق معمول جلسات گذشته، اعضا به بیان نظرات و دیدگاه‌های خود در رابطه با فعالیت‌های گروه و همچنین کار با گنو/لینوکس
و نرم‌افزارهای آزاد پرداختند. از بحث درباره مفهوم و جایگاه امنیت در گنو/لینوکس تا معایب و مزایای systemd در گنو/لینوکس. همچنین
در انتهای جلسه از  اعضای گروه خواسته شد که در صورت تمایل، موضوعات و مباحثی که تمایل هستند در گروه بیشتر با آنها آشنا شوند را مطرح
کنند. از مواردی که مطرح شد می‌توان به مباحث زیر اشاره نمود:

* آموزش ‪SDN (Software-Defined Networking)‬
* آموزش کامپایل و کار با Makefile ها در گنو/لینوکس
* آموزش Docker
* و نحوه راه‌اندازی سرویس ایمیل در سرورهای گنو/لینوکسی

از علاقمند درخواست می شود در صورت تمایل به معرفی و ارائه در رابطه با هر یک از مباحث فوق، از طریق یکی از راه‌های ارتباطی گروه
جهت اعلام آمادگی اقدام نمایند.

این جلسه در ساعت ۱۹:۳۰ خاتمه یافت.