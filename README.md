<p align="center"> <img src="http://up.upinja.com/ptx2r.jpg" width="240">
<h1><p align="center">جوکرتیم
<h2><p align="center">سرعت 💠 دقت 💠 قدرت
<div align="center">
    <a href="https://telegram.me/Jwker_Bot">
        <img src="http://upir.ir/951/guest/Untitled-5.png" hspace="10" width="150">
    </a>
    <a href="https://telegram.me/Jwker_team">
        <img src="http://upir.ir/951/guest/Untitled-7.png" hspace="10" width="150">
    </a>
    <a href="https://telegram.me/Mr_JwKeR">
        <img src="http://upir.ir/951/guest/Untitled-6.png" width="150">
        
<h3><p dir="rtl">تبچی رباتی هوشمند, بسیار ساده و البته رایگان جهت امور تبلیغاتی در تلگرام است.<br>
ویرایش شده توسط <a href="https://telegram.me/Jwker_team">تیم جوکر</a> برپایه اخرین نسخه <a href="https://valtman.name/telegram-cli">تلگرام</a>.
<br>
<h3 align="right"> <strong> نصب و راه‌اندازی</strong> 🚀
</h3>
<hr>
<h4 dir="rtl">ابتدا سورس <em>تبچی</em> را کپی کرده و پیش‌زمینه‌ها را نصب کنید.</h4>
<h6>(موارد زیر را در ترمینال وارد کنید)</h6>
<pre>
<span>git clone https://github.com/JwkerTeam/TaBchi.git && cd TaBchi && chmod 777 install.sh && ./install.sh</span>
</pre>
<h4 dir="rtl"> برای ساخت ربات جدید <strong>lua creator.lua</strong> را وارد کنید.
</h4>
<pre>
<span>lua creator.lua</span>
</pre>
<h4 dir="rtl">حال با توجه به شناسه ای که برای ربات جدید داده شده تبچی خود را راه‌اندازی کنید.
<br>مثال:</h4>
<h6 dir="rtl">در صورتی ک ردیس تنظیم نشده است آن را تنظیم کنید.</h6>
<pre>
<span>دستوری برای راه اندازی مجدد ردیس#</span>
<span>sudo service redis-server restart</span>
<span>دستوری برای راه اندازی ردیس#</span>
<span>sudo service redis-server start</span>
<span></span>
<span>./tabchi-1.sh</span>
</pre>
<h5 dir="rtl">توجه داشته باشید برای اولین بار که ربات را میسازید از شما شناسه عددی مدیر ربات (شما و یا هرکس که می خواهید مدیر ربات شود) ، شماره ربات و کد ورود به حساب کاربری خواسته می‌شود.
<h6 dir="rtl"> شما می توانید با استفاده از ربات <a href="https://telegram.me/userinfobot">@userinfobot</a> شناسه عددی خود را بدست آورید.</h6>
<h6 dir="rtl">از <a href="#help">راهنمای‌تبچی</a> برای آشنا شدن با طرز کار رباتتان استفاده کنید.</h6>
<br>
<h3 align="right"><strong>جلوگیری از قطع شدن عملکرد تبلیغ‌گر</strong>🛡
<hr>
<h4 dir="rtl">یکی از مشکلات کار با SSH، قطع شدن آن در زمان قطع اتصال اینترنت است.<br>وقتی اتصال اینترنت قطع می‌شود اجرای تمامی برنامه‌ها و فرامینی که در حال استفاده از SSH بودند، متوقف می‌شود. فرمان screen این‌جا به‌کمک شما می‌آید. کافی است این دستور را قبل از دستورراه‌اندازی تبلیغ‌گر قرار دهید.</h4>
<h6 dir="rtl">مثال:</h6>
<pre>
<span><strong>screen ./tabchi-1.sh</strong></span>
</pre>
<h4 dir="rtl">برای خارج شدن از محیط screen کلید‌های ترکیبی Ctrl+A و سپس کلید D را بفشارید.<br>برای مشاهده فهرست screen های موجود می‌توانید از دستور<strong>  screen -ls  </strong>  استفاده کنید.<br>این دستور فهرست تمامی screen های در حال اجرا را نمایش می‌دهد.<br>برای مشاهده screen اجرا‌شده، کافی است دستور زیر را وارد کنید:</h4>
<pre>
<span><strong>screen -r [screen name]</strong></span>
</pre>
<h4 dir="rtl">برای استفاده به شکل آنتی کرش از دستور زیر استفاده کنید:</h4>
<pre>
<span><strong>screen ./anticrash.sh</strong></span>

