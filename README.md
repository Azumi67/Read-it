# new-post
سلام . من بیماری نرمی استخوان دارم و مانند قدیم نمیتونم فعال باشم . مشکلات درس و سایر موارد هم هست. این صفحه بیشتر برای پروژه های شخصی خودم و مدرسه ام میباشد . استفاده کردن از این برنامه ها به هر نحوی و در هر زمینه ای با مسِولیت خود شما است. این چند مورد را میخواستم اینجا بنویسم

- ممنونم از اینکه بهم ایمیل میدید و بهم لطف دارید. من چندین مورد از ایمیل ها را اینجا پاسح میدم.
- ایپی ثابت در geneve باعث قطعی شما نمیشه بلکه آن روش در اون دیتاسنتر مربوطه میتونه بسته بشه و بهتره از encapsulation ترکیبی استفاده نمایید که مشکل شمل حل بشه. بعدا تصمیم دارم که چندین ایپی لوپ به این برنامه اضافه کنم که بشه به راحتی بین ایپی های لوکال متفاوت تغییر داد.من خودم شخصا مشکلی در این زمینه نداشتم
- در مورد DR و IPS سوال کردید. من این مورد را کار کردم و بعدا که حالم بهتر بود اضافه خواهم کرد. توضیحی در این مورد میدهم. در این روش ما یک روت مستقیم بین دو سرور اضافه میکنیم و با لود بالانس ترافیک را بر روی پورت های مختلف و همچنین با ایپی پرایوت داخل سرور که بر روی ایپی لوکال روت مستقیم فروارد کردیم، میفرستیم . امنیت آن هم با IPSEC برقرار میکنم. پس اول یک تانل مستقیم ایجاد میشه و یک ایپی لوکال دریافت میکنیم. سپس ترافیک را بر روی ایپی پرایوتی که در اینترفیس اصلی سرور ایجاد کردیم، میفرستیم و بر روی پورت های مختلف میفرستیم که حالت لود بالانس داشته باشد. در آخر هم امنیت این ارتباط را با IPSEC برقرار میکنیم. همانطور که میبینید کمی زمان بر و سخت خواهد بود.
- یک آموزش برای IPSEC در خود پروژه قرار دادم و میتونید از آن برای نمونه استفاده نمایید
- به تانل ها گزینه ویرایش را اضافه میکنم که نیاز نباشه هر دفعه ار اول کانفیگ را انجام دهیم.
- مورد دیگر که میخواهم بر روش کار کنم تانل 64 با encryption داخلی میباشد . سپس پورت فوروارد را با IPSEC امن تر میکنم و این روش هم نیازمند زمان مناسبی برای نوشتنش میباشد.
- یک مورد دیگر که میخواهم کار کنم vxlan و ایجاد brige در اینترفیس دو سرور میباشد و این هم نتیجه مناسبی رو میده. یعنی ایجاد bridge جدا ار کامند های vxlan میباشد
- و ایمیل میدید که rathole و reverse tls چرا سرور ایران اضافه نمیشه. بله این هم در فکرش هستم.
- مورد آخر اینکه اسکریپت ها خیلی تست میشه و تقریبا بدون باگ هست. اگر مشکلی در اجرای تانلی یا روشی دارید، دلیلش چیز دیگری هست. به باگ ربطی ندارد.
- ممنونم 
