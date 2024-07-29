# new-post
سلام . من بیماری روماتیسم دارم و مانند قدیم نمیتونم فعال باشم اما مواقعی که حالم خوب باشد و free باشم مانند قدیم در حد توانم اپدیت خواهم داد . مشکلات درس و سایر موارد هم هست. این صفحه بیشتر برای پروژه های شخصی خودم میباشد و استفاده کردن از این برنامه ها به هر نحوی و در هر زمینه ای با مسِولیت خود شما است. این چند مورد را میخواستم اینجا بنویسم.

از دوستانی که پیام داده بودند و نکاه نکردم عذر میخوام و اینکه اکانتم رو دوستم پاک کرده بود چون یک هفته به دلیل بیماری مدرسه نرفته بودم.
- نوشتن این پروزه ها زمان بر است و بیشتر به خاطر علاقه شخصی اینکار را میکنم پس این احتمالش هست که feature های مد نظر شما وارد این پروژه نشود چون هدف من نه فروش و نه پول در آوردن است. این صفحه تنها برای ایده های خودم میباشد.( امکانش هست که آموزشی برای پروژه هایم نوشته نشود چون برای من دردسر ساز بوده)
- ممنونم از اینکه بهم ایمیل میدید و بهم لطف دارید. من چندین مورد از ایمیل ها را اینجا پاسخ میدم.
- ایپی ثابت در geneve باعث قطعی شما نمیشه بلکه آن روش در اون دیتاسنتر مربوطه میتونه بسته بشه و بهتره از encapsulation ترکیبی استفاده نمایید که مشکل شمل حل بشه. بعدا تصمیم دارم که چندین ایپی لوپ به این برنامه اضافه کنم که بشه به راحتی بین ایپی های لوکال متفاوت تغییر داد.من خودم شخصا مشکلی در این زمینه نداشتم
- در مورد DR و IPS سوال کردید. من این مورد را کار کردم و بعدا که حالم بهتر بود اضافه خواهم کرد. توضیحی در این مورد میدهم. در این روش ما یک روت مستقیم بین دو سرور اضافه میکنیم و با لود بالانس ترافیک را بر روی پورت های مختلف و همچنین با ایپی پرایوت داخل سرور که بر روی ایپی لوکال روت مستقیم فروارد کردیم، میفرستیم . امنیت آن هم با IPSEC برقرار میکنم. پس اول یک تانل مستقیم ایجاد میشه و یک ایپی لوکال دریافت میکنیم. سپس ترافیک را بر روی ایپی پرایوتی که در اینترفیس اصلی سرور ایجاد کردیم، میفرستیم و بر روی پورت های مختلف فواوارد میکنیم که حالت لود بالانس داشته باشد (هم از ایپی لوکال و هم از پرایوت ایپی اینترفیس اصلی استفاده میشود). در آخر هم امنیت این ارتباط را با IPSEC برقرار میکنیم. همانطور که میبینید کمی زمان بر و سخت خواهد بود.(لود بالانس بر روی TCP میباشد)
- میخوام سوکت تایپ های محتلف را برای IPSEC تست کنم
- یک آموزش برای IPSEC در خود پروژه قرار دادم و میتونید از آن برای نمونه استفاده نمایید
- به تانل ها گزینه ویرایش را اضافه میکنم که نیاز نباشه هر دفعه ار اول کانفیگ را انجام دهیم.
- مورد دیگر که میخواهم بر روش کار کنم تانل 64 با encryption داخلی میباشد . سپس پورت فوروارد را با IPSEC امن تر میکنم و این روش هم نیازمند زمان مناسبی برای نوشتنش میباشد.
- یک مورد دیگر که میخواهم کار کنم vxlan و ایجاد bridge در اینترفیس دو سرور میباشد و این هم نتیجه مناسبی رو میده. یعنی ایجاد bridge جدا ار کامند های vxlan میباشد
- مورد آخر اینکه اسکریپت ها خیلی تست میشه و تقریبا بدون باگ هست. اگر مشکلی در اجرای تانلی یا روشی دارید، دلیلش چیز دیگری هست. به باگ ربطی ندارد.
- ممنونم 
