<div dir="rtl">

# فیلیمو چیست؟
[فیلیمو](http://filimo.com/invite/NabiKAZ/a8ca) محصول آپارات است. آرشیوی از بهترین فیلم‌های ایران و جهان شامل فیلم سینمایی، سریال‌، مستند و فیلم-تئاترهایی که به راحتی برای تماشا در اختیار شما قرار گرفته است. جهت اطلاعات بیشتر به سایت [فیلیمو](http://filimo.com/invite/NabiKAZ/a8ca) مراجعه نمائید.

![filimo_main_page](https://user-images.githubusercontent.com/246721/34075273-f028010c-e2d6-11e7-9e77-083408d0ebca.png)

در فیلیمو بی‌وقفه فیلم ببینید.

# این برنامه چکار میکند؟
در صورتی که [اشتراک فیلیمو](http://filimo.com/invite/NabiKAZ/a8ca) تهیه کرده‌اید، به کمک این برنامه می‌توانید فیلم‌های سایت فیلیمو را روی سیستم خود دانلود و به‌شکل آفلاین آن‌ها را مشاهده کنید.

# نیازمندی‌ها
* [تهیه اشتراک فیلیمو](http://filimo.com/invite/NabiKAZ/a8ca)
* [برنامه PHP (حداقل نسخه 5.4)](http://php.net)
* [برنامه FFmpeg](http://ffmpeg.org)
* خط فرمان ویندوز یا لینوکس

# راهنمای استفاده
* ابتدا از طریق این لینک در فیلیمو ثبت نام کنید و حق اشتراک مورد نیاز خود را خریداری نمائید:
[http://filimo.com/invite/NabiKAZ/a8ca](http://filimo.com/invite/NabiKAZ/a8ca)

* از نصب [PHP](http://php.net/) و نسخه‌ی نصب شده بر روی سیستم خود توسط دستور `php -v` اطمینان حاصل کنید.

* از نصب [FFmpeg](http://ffmpeg.org) بر روی سیستم خود توسط دستور `ffmpeg` اطمینان حاصل کنید.

* در مسیر برنامه و خط فرمان سیستم‌عامل خود دستور زیر را وارد کنید:

```
php download.php
```
* پس از آن یوزر و پسورد از شما خواسته می‌شود و پس از لاگین کد ویدیوی مورد نظر خود که در آدرس بار مرورگر مشاهده می‌کنید را وارد کنید. پس از آن کیفیت‌های در دسترس نشان داده می‌شوند که یکی را انتخاب کنید و دانلود در پس‌زمینه آغاز خواهد شد.

* فیلم دانلود شده در شاخه download قابل دسترس می‌باشد.

![filimo_code](https://user-images.githubusercontent.com/246721/34075283-1733209c-e2d7-11e7-88b6-e4a7b87b34a2.png)


# گزارشگیری دانلود
دستور `php -S localhost:8000` را وارد کنید. سپس در مرورگر خود، آدرس `http://localhost:8000/stats.php` را باز کنید. بدین صورت می‌توانید گزارش و مشخصات همه‌ی فیلم‌های دانلود شده و میزان درصد دانلود آنها را مشاهده کنید.



# توقف دانلود
اگر از ویندوز استفاده می‌کنید توسط دستور `tasklist | find "ffmpeg"` شماره پروسه را پیدا کنید و توسط `taskkill /f /pid <PID>` آن را متوقف کنید. اگر از لینوکس استفاده می‌کنید، توسط دستور `ps a | grep ffmpeg` شماره پروسه را پیدا و توسط `kill -9 <PID>` آن را متوقف کنید.

# امنیت
توجه داشته باشید که کوکی مربوط به اطلاعات لاگین شما، به شکل پیش‌فرض در شاخه config نگهداری می‌شوند و اگر کسی به آن دسترسی داشته باشد ممکن است بتواند به اکانت شما دسترسی پیدا کند. بنابراین در حفظ این شاخه کوشا باشید و یا پس از اتمام کار خود، آن را حذف کنید.

# رفع مسئولیت
* جهت حفظ حقوق مؤلفین، لطفاً و خواهشاً فایل فیلم‌های دانلود شده را به هیچ وجه بازنشر نکنید. انجام اینکار غیرقانونی بوده و مسئولیت آن متوجه شماست.

* این برنامه برای استفاده رایگان بوده و قابل فروش نیست و با ذکر منبع می‌توانید منتشر کنید.

* این برنامه منبع‌باز بوده که یکی از دلایل آن، جنبه آموزشی اینکار می‌باشد.

* این برنامه در نسخه آزمایشی خود قرار دارد و کد فعلی خیلی بهم ریخته است! اما در ویندوز و لینوکس خوب کار می‌کند :blush:

* اگر در هنگام کار با برنامه به مشکلی برخورد کردید، لطفاً از بخش [issues](/../../issues/new) مطرح فرمائید؛ در حد توان پاسخ خواهم داد.

# حمایت
* در صورتی که از این برنامه راضی بودید، لطفاً با دادن یک ستاره (:star:) (از بخش بالای سایت) من را خوشحال کنید! :wink:

* این یک پروژه تجاری نیست و سود مادی برای من ندارد و به صورت دلی:heart: انجام می‌شود. اما می‌دانید که برنامه‌نویسی کار خیلی وقت‌گیر و پر زحمتی است. اگر این پروژه برای شما مفید بود و دلتان خواست، لطفاً برای دلگرمی من می‌توانید هر مبلغی که مایل بودید هر چند ناچیز به صورت هدیه واریز کنید تا تبدیل به انرژی شود برای ادامه راه، بهبود، توسعه و رفع اشکالات احتمالی این پروژه در آینده.<br>
جهت پرداخت آنلاین از لینک زیر استفاده کنید و لطفاً حتماً در توضیحات آن، نام این پروژه را ذکر کنید:<br>
[https://zarinp.al/nabikaz](https://zarinp.al/nabikaz)<br>
همیشه از لطف شما سپاسگزارم :sweat_smile::rose:
