# Contributing · ساهم معنا

## English

Thanks for wanting to help. This is a small open project, and every bit of help counts.

### Ways to help

- **Report a bug.** Open an issue: what you did, what you expected, what happened.
- **Suggest an idea.** Open an issue, or start a thread in Discussions.
- **Improve the Arabic.** Arabic text in the app and docs is written in everyday Levantine (Shami) dialect, not formal Arabic.
- **Translate** to a new language.
- **Add spam numbers.** Send a pull request with new rows (see below).

### Before you send a pull request

- Big change? Open an issue first so we can talk about it.
- Keep each PR small and about one thing.
- Test your change before sending it.
- Never put API keys, passwords or personal data in any file.

### How to add numbers

Add one row per number to `spamdb.csv` (columns: `number,category,negative,positive,neutral,name`), in international format, for example `+9665...`. Only add numbers that really are spam or scam calls, and never add private people's numbers. Then set `version.txt` to today's date (`YYYY-MM-DD`) so the app picks up the change.

### Commit messages

One short sentence that says what changed, for example `Add 5 spam numbers`.

### License

By contributing you agree that your work is released under this project's license (see `LICENSE`).

## بالعربي

شكراً إنك حابب تساعد! المشروع صغير ومفتوح، وأي مساعدة بتفرق.

### كيف بتقدر تساعد

- **بلّغ عن مشكلة:** افتح issue وقلنا شو عملت، وشو كنت متوقع، وشو صار.
- **اقترح فكرة:** افتح issue أو ابدأ نقاش بـ Discussions.
- **حسّن النص العربي:** النصوص العربية بالتطبيق والوثائق بتنكتب بلهجة شامية عادية، مو فصحى.
- **ترجم** للغة جديدة.
- **ضيف أرقام سبام:** ابعتلنا pull request فيه الأسطر الجديدة (شوف تحت).

### قبل ما تبعت pull request

- التغيير كبير؟ افتح issue أول وخلينا نحكي فيه.
- خلّي كل PR صغير وبشي واحد.
- جرّب تغييرك قبل ما ترسلو.
- لا تحط مفاتيح API ولا كلمات سر ولا معلومات شخصية بأي ملف.

### كيف بتضيف أرقام

ضيف سطر لكل رقم بملف `spamdb.csv` (الأعمدة: `number,category,negative,positive,neutral,name`) بالصيغة الدولية، مثلاً `+9665...`. ضيف بس الأرقام اللي فعلاً سبام أو نصب، وما تضيف أرقام ناس عاديين أبداً. وبعدين حط تاريخ اليوم بـ `version.txt` (`YYYY-MM-DD`) ليلقط التطبيق التغيير.

### رسائل الـ commit

جملة وحدة قصيرة بتقول شو تغيّر، مثلاً `Add 5 spam numbers`.

### الرخصة

لما بتساهم، بتوافق إنو شغلك بينزل تحت رخصة المشروع (شوف `LICENSE`).
