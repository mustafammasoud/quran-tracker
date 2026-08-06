#  القرآن — متتبع الحفظ والمراجعة

تطبيق ويب بسيط (ملف HTML واحد) لمتابعة حفظ ومراجعة القرآن الكريم، سورة سورة، بشكل بصري وسهل.

## المميزات

- **شبكة السور (114 سورة):** كل سورة مربّع مستقل بيتلوّن حسب حالتها:
  - ⚪ رمادي — لم تبدأ
  - 🟡 أصفر — قيد الحفظ
  - 🟢 أخضر — محفوظة
  - 🔵 أزرق — مراجعة ممتازة
- **البحث السريع:** اكتب اسم السورة (أو رقمها) في مربع البحث، اختر النتيجة، والمربع بتاعها هيعمل Scroll تلقائي ليها ويومض عشان تلاقيها بسرعة.
- **تنبيه المراجعة:** أي سورة محفوظة ومرّ عليها وقت طويل من غير مراجعة، بتاخد إطار لوني (أصفر/برتقالي/أحمر) حسب عدد الأيام، وبتظهر في قائمة "بحاجة للمراجعة".
- **تبويب الأجزاء:** نسبة إنجاز كل جزء من الثلاثين جزء، محسوبة بدقة حسب عدد الآيات.
- **تبويب الإحصائيات:** عدد السور والأجزاء المكتملة، نسبة الإنجاز الكلية، عدد الصفحات التقريبي، أطول سلسلة أيام متتالية والسلسلة الحالية، ورسم بياني لآخر 30 يوم.
- **الأهداف:** أضف أهدافك الخاصة (مثلاً "حفظ سورة الكهف")، وحدّد نسبة تقدمك يدويًا بشريط تمرير.
- **التقويم:** خريطة حرارية (Heatmap) لآخر 91 يوم توضح نشاطك اليومي.
- **حفظ محلي بالكامل:** كل بياناتك تتخزن في متصفحك فقط (localStorage) — مفيش سيرفر ومفيش تسجيل دخول، وبياناتك متفضل عندك حتى لو قفلت الصفحة (إلا لو مسحت بيانات المتصفح).

## طريقة الاستخدام

1. افتح الملف `quran-tracker.html` في أي متصفح (كمبيوتر أو موبايل).
2. دوس على أي سورة في الشبكة لفتح نافذة تغيير حالتها، واختار الحالة المناسبة.
3. لو السورة محفوظة، حدّد تاريخ آخر مراجعة لها.
4. استخدم مربع البحث فوق الشبكة لو حابب توصل لسورة معيّنة بسرعة.
5. تنقّل بين التبويبات (القلب / الأجزاء / الإحصائيات / الأهداف / التقويم) من الشريط العلوي.

## ملاحظة تقنية

الملف عبارة عن HTML واحد فيه كل الكود (CSS + JavaScript) من غير أي اعتماد على مكتبات خارجية أو اتصال إنترنت — يعني هيشتغل حتى من غير نت بمجرد ما تفتحه.

---

# Heart of the Qur'an — Memorization & Review Tracker

A simple, single-file HTML web app for tracking Qur'an memorization and review, surah by surah, in a clear visual way.

## Features

- **Surah grid (all 114 surahs):** each surah is its own tile, colored by status:
  - ⚪ Gray — not started
  - 🟡 Yellow — in progress
  - 🟢 Green — memorized
  - 🔵 Blue — excellent review
- **Quick search:** type a surah's name (or number) in the search box, pick a result, and its tile automatically scrolls into view and pulses so you can spot it instantly.
- **Review reminders:** any memorized surah that hasn't been reviewed in a while gets a colored ring (yellow/orange/red depending on how many days), and shows up in the "needs review" list.
- **Juz tab:** completion percentage for each of the 30 juz', weighted accurately by verse count.
- **Stats tab:** memorized surahs/juz' counts, overall completion percentage, approximate page count, longest and current daily streak, and a 30-day activity chart.
- **Goals:** add your own custom goals (e.g. "memorize Surah Al-Kahf") and track progress manually with a slider.
- **Calendar:** a 91-day heatmap showing your daily activity.
- **Fully local storage:** all your data is saved only in your browser (localStorage) — no server, no login, and your data stays put even after closing the page (unless you clear your browser data).

## How to use

1. Open `quran-trakecr.html` in any browser (desktop or mobile).
2. Tap any surah tile to open its status dialog and pick the right status.
3. If a surah is memorized, set the date of your last review.
4. Use the search box above the grid to jump straight to a specific surah.
5. Switch between tabs (Heart / Juz / Stats / Goals / Calendar) from the top navigation bar.

## Technical note

The whole app is a single HTML file containing all the CSS and JavaScript, with no external library dependencies or internet connection required — it works fully offline once opened.