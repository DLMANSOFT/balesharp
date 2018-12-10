# balesharp
Bale Messenger Bot Sample (C#)

سمپل اتصال به سرور بله برای ساختن بوت در سی شارت
بله از زیر ساخت وب سوکت کانکشن استفاده میکند که در سی شارپ ماکروسافت به سختی میتوان ایمپلمنت درستی برای کامپوننت پیدا کرد
در حال حاضر دو تا از کامل ترین پیاده سازی های وب سوکت که من استفاده کردم اینها هستن:

* https://github.com/henkosch/JsonWebSocket.Net
* https://github.com/sta/websocket-sharp

از هردوی اینها برای اتصال به سرور بله میشود استفاده کرد
ولی من از کتابخانه دومی استفاده کردم

همچنین برای ارسال فایل در بله نیازمند چک سام هستین که برای ان باید از کتابخانه زیر استفاده شود
* https://github.com/force-net/Crc32.NET

و برای تبادل اطلاعات بصورت جی سون و تبدیل اون ار کتابخانه Json.net
* https://www.newtonsoft.com/json

در زیر نمای این برنامه نمایش داده شده است
![Image](https://mahdiit.github.io/balesharp/pic3.png)

* VS 2017
* .Net 4.6.2 WinForm C#

1. توکن را در این قسمت وارد کنید
2. لاگ ارتباطات برنامه در این جا درج میشود
3. جهت ارتباط با سرور یا قطع آن 
4. لاگ پیامهای دریافتی از سرور
5. ارسال پیام متنی
6. دکمه ارسال پیام

![Image](https://mahdiit.github.io/balesharp/pic2.png)
