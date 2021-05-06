محمد سروش_ 97440230 _ تمرین پنجم
سوال اول.
ابتدا با دستور cd وارد فایلمان میشویم. سپس دستورات زیر را به ترتیب وارد میکنیم.
git config --global user.name “Your Username”
git config --global user.email “your Gmail”


سوال دوم.
:.gitignore
این دستور فایل های گفته شده به گیت را نادیده میگیرد.
:.git
یک دستور برای تغییر فایل های سیستم است
:git pull
اخرین تغییرات را دریافت و ابدیت میکند
:branch
دستوری مثل backup است و میتوان یک نسخه اولیه از برنامه تهیه کرد تا اگر در تغییرات به مشکل
خوردیم، نسخه اولیه به کمکمان بیاید.


سوال سوم.
ابتدا یک directory ایجاد و سپس دستورات زیر را در پوشه مورد نظر اجرا میکنیم
git init
git add –all
git commit –m “Your commit”
git branch -M main
git remote add origin “Your repository’s URL”
git push -u


سوال چهارم.
Uptime
systemd-analyze
systemd-analyze blame
systemd-analyze critical-chain
