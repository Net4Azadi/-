# استفاده از سرور داخلی

## نحوه جلوگیری از عبور ترافیک داخلی از سرور پروکسی

ایده‌آل‌ترین حالت اینه که ترافیک داخلی ایران به سمت سرور پروکسی ارسال نشه. برای این‌منظور می‌تونیم توی کلاینت‌های مختلف با Routing Rules تعریف‌کنیم این‌ترافیک از پروکسی عبور نکنه و فقط ترافیک خارجی به سمت سرور پروکسی ارسال بشه.

[نحوه جلوگیری از عبور ترافیک داخلی از سرور پروکسی](https://telegra.ph/%D9%86%D8%AD%D9%88%D9%87-%D9%85%D8%B3%D8%AF%D9%88%D8%AF%D8%B3%D8%A7%D8%B2%DB%8C-%D8%B3%D8%A7%DB%8C%D8%AA%E2%80%8C%D9%87%D8%A7-%D9%88-%D8%A7%D9%BE%E2%80%8C%E2%80%8C%D9%87%D8%A7%DB%8C-%D8%A7%DB%8C%D8%B1%D8%A7%D9%86%DB%8C-%D8%A7%D8%B2-%D8%B3%D9%85%D8%AA-%DA%A9%D8%A7%D8%B1%D8%A8%D8%B1-02-15)

## ReverseTlsTunnel - تانل معکوس
دراین روش بجای اینکه از سرور داخل به خارج تانل بزنیم داریم از سرور خارج به ایران میزنیم برای همین در برخی مواقع حتی ممکنه روی سرور فیلتر شده هم جواب بده!!

با ۲روش میشه انجامش داد که یکی با خود پنل x-ui هستش یکی هم پروژه ReverseTlsTunnel

1. x-ui:

[آموزش تانل معکوس](https://www.youtube.com/watch?v=jCg6Yci7a5U)

[chain](https://www.youtube.com/watch?v=0SBtJ11EcjA)

[ ریورس تانل , v2ray , حرفه ای و بدون اختلال با پنل x-ui ](https://www.youtube.com/watch?v=2ieccbVzlUw)

2. [ReverseTlsTunnel](https://github.com/radkesvat/ReverseTlsTunnel)


3. [ریورس پروکسی grpc / معکوس تمام سایت](https://www.youtube.com/watch?v=QBEnXWTyQwE)


## وردپرس با پنل سنایی و علیرضا

[ پنل xui و وردپرس رو کنار هم داشته باش! اسکریپت خودکار WUI  تک پورت کردن پنل سنایی و علیرضا ](https://www.youtube.com/watch?v=OksLefIcUxc)



همونطور که میدونین استفاده از پنل های xui بدون اینکه سایتی در پس زمینه باشه میتونه احتمال فیلتر شدن آیپی سرور و دامنه رو افزایش بده . به همین علت اسکریپت WUI میتونه برای ما وردپرس رو در کنار پنل xui نصب کنه و مارو به حالت عادی نزدیکتر کنه. با اینکار یک سایت وردپرسی روی دامنه شما ایجاد میشه و با یک مسیر مخفی میتونیم به  پنلمون دسترسی داشته باشیم.


[WUI (WordPress + XUI Panel)](https://github.com/azavaxhuman/WUI)


## Namizun - نامیزون
با استفاده از نامیزون مقدار مصرف ترافیک رو نامتعادل کنید اینطوری هم دیرتر شناسایی میشه هم اگه جایی مشکل مصرف منصفانه داشتید میتونید بااین روش دورش بزنید:

[گیتهاب پروژه](https://github.com/salehi/namizun)

[آموزش](https://www.youtube.com/watch?v=rFXG6SdcqWw)

## Speedtest - تست سرعت
[Client]
* https://fiber.google.com/speedtest/
* https://speed.cloudflare.com/
* https://www.speedtest.net/

[Server]
```
wget -qO- bench.sh | bash
```

# Gost

[آموزش اجرای تانل معکوس Gost بر روی سرور ایران](https://telegra.ph/%D8%AA%D8%A7%D9%86%D9%84-%D9%85%D8%B9%DA%A9%D9%88%D8%B3-Gost-%D8%A8%D8%A7-%D8%A7%D8%B3%D8%AA%D9%81%D8%A7%D8%AF%D9%87-%D8%A7%D8%B2-CDN-03-13)



# Port to Port

[ آموزش تانل سرور ایران به چند سرور خارج با روش Port to Port ](https://www.youtube.com/watch?v=AplqTJDN1YY)


# چرا NGINX انقدر وحشتناک سریعه؟!

[چرا NGINX انقدر وحشتناک سریعه؟!](https://threadreaderapp.com/thread/1761266188871496093.html)