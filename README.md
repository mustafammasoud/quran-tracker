# القرآن — متتبع الحفظ والمراجعة

تطبيق ويب بملف HTML واحد لمتابعة حفظ ومراجعة القرآن الكريم، سورة سورة، بشكل بصري وسهل — يعمل بالكامل دون إنترنت.

## المميزات

### القلب (سور القرآن)

- **شبكة السور (114 سورة):** كل سورة مربّع مستقل يتلوّن حسب حالتها:
  - ⚪ رمادي — لم تبدأ
  - 🟡 أصفر — قيد الحفظ
  - 🟢 أخضر — محفوظة
  - 🔵 أزرق — مراجعة ممتازة
- **البحث السريع:** اكتب اسم السورة (أو رقمها) في مربع البحث، اختر النتيجة، والمربع يعمل Scroll تلقائي إليها ويومض لتجدها بسرعة.
- **تتبع الآيات بدقة:** سجّل نطاق الآيات المحفوظة (من آية إلى آية) مع شريط تقدم دقيق لكل سورة.
- **خطة اليوم الذكية:** تولّد تلقائيًا خطة يومية من أهدافك (مثل "حفظ سورة الكهف") — تقترح الآيات المحددة للحفظ والمراجعات المستحقة، مع علامة إتمام لكل بند.
- **تنبيه المراجعة:** أي سورة محفوظة ومرّ عليها وقت طويل من غير مراجعة تأخذ إطارًا لونيًا (أصفر/برتقالي/أحمر) حسب عدد الأيام، وتظهر في قائمة "بحاجة للمراجعة".

### نظام المراجعة الذكي (SRS)

- كل سورة محفوظة لها "صندوق" (1-5) بفترات متدرجة: 1، 3، 7، 14، 30 يوم.
- مراجعة ناجحة ترفع السورة لصندوق أعلى (فترة أطول)، والفشل يخفضها.
- **وضع الاختبار الذاتي:** اختبر نفسك في أي سورة — يعرض أول كلمات الآية، تحاول إكمالها، وتقيّم نفسك (أتقنتها/نسيتها) والنتيجة تؤثر على نظام المراجعة.

### رحلتي

- **محطات الرحلة:** 6 محطات من بداية الرحلة حتى ختمة القرآن كاملة، مع تواريخ الإنجاز.
- **سجل الرحلة:** كل إنجاز (سورة محفوظة، محطة محققة) مرتب زمنيًا.

### الأجزاء

- نسبة إنجاز كل جزء من الثلاثين جزء، محسوبة بدقة حسب عدد الآيات.

### الإحصائيات

- عدد السور والأجزاء المكتملة، نسبة الإنجاز الكلية، عدد الصفحات التقريبي.
- أطول سلسلة أيام متتالية والسلسلة الحالية، ورسم بياني لآخر 30 يوم.
- **أرقام قياسية:** أكبر عدد آيات في يوم، أسرع سورة حفظتها، أطول جلسة.
- **تحليل الأسبوع:** تقييم الحفظ والمراجعة والاستمرارية + أكثر الأيام نشاطًا.
- **تقرير أسبوعي ذكي:** ملخص أدائك مع أضعف نقطة ونصيحة مخصصة.
- **خطة الختمة التقديرية:** تقدير موعد ختمة القرآن حسب متوسط آياتك اليومية.

### الأهداف

- أضف أهدافك الخاصة (مثل "حفظ سورة الكهف") وحدّد نسبة تقدمك يدويًا بشريط تمرير.
- **إعادة ترتيب بالسحب والإفلات** حسب الأولوية.

### الإنجازات

- 18 شارة تتفتح تلقائيًا عند تحقيق إنجازات (أول سورة، 10 سور، سلسلة أسبوع، ورد الفجر، وغيرها).

### التقويم

- خريطة حرارية (Heatmap) لآخر 91 يوم توضح نشاطك اليومي (حفظ/مراجعة/تلاوة/اختبار).

### الإعدادات

- **وضع ليلي (Dark Mode):** زر تبديل سريع في الهيدر مع حفظ التفضيل.
- **هدف يومي:** حدد عدد الآيات المستهدفة يوميًا.
- **يوم إنقاذ:** تفعيل يوم إنقاذ شهريًا للحفاظ على السلسلة.
- **تذكير يومي:** إشعار متصفح يومي الساعة 8 مساءً.
- **طباعة تقرير الإنجاز:** تقرير منسق RTL قابل للطباعة.
- **تصدير/استيراد البيانات:** نسخة احتياطية بصيغة JSON.
- **إعادة تعيين/حذف البيانات.**

### تجربة المستخدم

- **شريط تنقل سفلي** على الموبايل (≤640px).
- **اختصارات لوحة المفاتيح:** H قلب، J رحلتي، U أجزاء، S إحصائيات، G أهداف، B إنجازات، C تقويم، / بحث.
- **أونبوردنج:** نافذة ترحيب تشرح الحالات والألوان عند أول استخدام.

## طريقة الاستخدام

1. افتح الملف `quran-tracker.html` في أي متصفح (كمبيوتر أو موبايل).
2. اضغط على أي سورة في الشبكة لفتح نافذة تغيير حالتها، واختر الحالة المناسبة.
3. سجّل نطاق الآيات المحفوظة (من آية إلى آية) أو عددًا تقريبيًا.
4. لو السورة محفوظة، حدّد تاريخ آخر مراجعة لها.
5. استخدم مربع البحث فوق الشبكة للوصول لسورة معيّنة بسرعة.
6. أضف أهداف "حفظ سورة" لتوليد خطة يومية ذكية.
7. تنقّل بين التبويبات من الشريط العلوي (أو السفلي على الموبايل).

## اختصارات لوحة المفاتيح

| المفتاح | الوظيفة            |
| ------- | ------------------ |
| `H`     | سور القرآن (القلب) |
| `J`     | رحلتي              |
| `U`     | الأجزاء            |
| `S`     | الإحصائيات         |
| `G`     | الأهداف            |
| `B`     | الإنجازات          |
| `C`     | التقويم            |
| `/`     | البحث السريع       |

## ملاحظة تقنية

الملف عبارة عن HTML واحد فيه كل الكود (CSS + JavaScript) من غير أي اعتماد على مكتبات خارجية أو اتصال إنترنت — يعني هيشتغل حتى من غير نت بمجرد ما تفتحه. البيانات محفوظة محليًا في متصفحك (localStorage) ولا تُرسل لأي خادم.

---

# Heart of the Qur'an — Memorization & Review Tracker

A single-file HTML web app for tracking Qur'an memorization and review, surah by surah, in a clear visual way. Works fully offline.

## Features

### Heart (Surah Grid)

- **All 114 surahs** as color-coded tiles: gray (not started), yellow (in progress), green (memorized), blue (excellent review).
- **Quick search:** type a surah's name or number, pick a result, and its tile auto-scrolls into view and pulses.
- **Verse-level tracking:** log exact verse ranges (from-to) with a precise progress bar per surah.
- **Smart daily plan:** auto-generated from your goals (e.g. "memorize Surah Al-Kahf") — suggests specific verses to memorize and due reviews, with checkboxes.
- **Review reminders:** memorized surahs overdue for review get colored rings (yellow/orange/red) and appear in the "needs review" list.

### Smart Review System (SRS)

- Each memorized surah has a box (1-5) with graduated intervals: 1, 3, 7, 14, 30 days.
- Successful review moves the surah up a box (longer interval); failure moves it down.
- **Self-test mode:** test yourself on any surah — shows the first words of a verse, you complete it, and self-assess (mastered/forgot), affecting the SRS.

### Journey

- **6 milestones** from starting your journey to completing the full Qur'an, with achievement dates.
- **Timeline log** of all achievements (memorized surahs, milestones).

### Juz

- Completion percentage for each of the 30 juz', weighted accurately by verse count.

### Stats

- Memorized surahs/juz' counts, overall completion %, approximate page count.
- Longest and current daily streak, 30-day activity chart.
- **Records:** most verses in a day, fastest surah memorized, longest session.
- **Weekly analysis:** hifz/review/consistency scores + most active day.
- **Smart weekly report:** performance summary with weakest point and personalized tip.
- **Khatma estimate:** estimated completion date based on your daily average.

### Goals

- Add custom goals (e.g. "memorize Surah Al-Kahf") and track progress with a slider.
- **Drag & drop reordering** by priority.

### Badges

- 18 badges unlock automatically (first surah, 10 surahs, week streak, Fajr wird, etc.).

### Calendar

- 91-day heatmap showing daily activity (hifz/review/recitation/test).

### Settings

- **Dark mode:** quick toggle in header with preference saved.
- **Daily goal:** set your target verses per day.
- **Grace day:** one monthly rescue day to protect your streak.
- **Daily reminder:** browser notification at 8 PM.
- **Print report:** RTL-formatted printable achievement report.
- **Export/import data:** JSON backup.
- **Reset/delete data.**

### UX

- **Bottom navigation** on mobile (≤640px).
- **Keyboard shortcuts:** H heart, J journey, U juz, S stats, G goals, B badges, C calendar, / search.
- **Onboarding:** welcome modal explaining the 4 states and colors on first use.

## How to use

1. Open `quran-tracker.html` in any browser (desktop or mobile).
2. Tap any surah tile to open its status dialog and pick the right status.
3. Log the verse range you memorized (from-to) or an approximate count.
4. If a surah is memorized, set the date of your last review.
5. Use the search box above the grid to jump straight to a surah.
6. Add "memorize surah" goals to generate a smart daily plan.
7. Switch between tabs from the top nav (or bottom nav on mobile).

## Keyboard shortcuts

| Key | Function           |
| --- | ------------------ |
| `H` | Heart (surah grid) |
| `J` | Journey            |
| `U` | Juz                |
| `S` | Stats              |
| `G` | Goals              |
| `B` | Badges             |
| `C` | Calendar           |
| `/` | Quick search       |

## Technical note

The whole app is a single HTML file containing all the CSS and JavaScript, with no external library dependencies or internet connection required — it works fully offline. All data is stored locally in your browser (localStorage) and never sent to any server.
