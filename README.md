آموزش نصب

داخل فایل cli.lua بروید در خط ۱و۲و۹ بجای idi یوزر سرور خودرا قرار دهید . اگر روی روت نصب میکنید idi/ را پاک کرده و به جای home کلمه root را جایگزین کنید . مثال : 
/home/idi/inline/utils.lua
تغییر دهید به 👇
 /root/inline/utils.lua
در خط ۱۰ و ۱۱ شناسه سودو و در خط1321شناسه بات api را قرار داده سپس فایل را سیو کنید و خارج شوید. 
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
طبق همین منوال به فایل api.lua بروید درخط ۴ بجای , idi یوزر سرور خودرا قرار دهید . اگر روی روت نصب میکنید idi/ را پاک کرده و به جای home کلمه root را جایگزین کنید  . به این صورت :
/root/inline/JSON.lua
 در خط ۵ توکن خود و در خط ۱۰ و ۱۲ شناسه سودو خود را بگذارید سپس در خط 168 بجای شناسه اولی شناسه ی بات cli و بجای شناسه دومی شناسه ی سودو خود را قرار دهید. 
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
حال ترمینال باز کنید و دستورات زیر را اجرا کنید
cd inline
chmod +x api.sh
chmod +x tg
chmod +x cli.sh
chmod +x on.sh
./cli.sh
از شما شماره ربات خواسته می‌شود پس از وارد کردن آن کد ورود به اکانت ربات cli خواسته می‌شود آن را هم وارد کنید. 
حال ترمینال جدید باز کنید و ربات api را با دستورات زیر ران کنید.

cd inline
./api.sh
قبل از دستورات لانچ screen بگذارید تا در صورت بستن ترمینال بات ها روشن بمونند

هر دو بات باید باهم روشن باشند!

نکته ی مهم 
۱. حتما به بات api دسترسی اینلاین بدهید 
۲.بعد از لانچ کردن حتما بات api رو با cli استارت کنید 


روشن کردن جفت بات ها با اتولانچ👇

killall tmux
killall screen
killall -9 bash
cd inline
./on.sh

اگر جایی به مشکل بر خوردید به پی وی بنده مراجعه کنید
