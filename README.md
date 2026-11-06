# block-number-data

Spam-number list for the **[block-number-android](https://github.com/tareknahas85-star/block-number-android)** call blocker. The app downloads it once a day, offline after that.

## Files
| File | What it is |
|---|---|
| `version.txt` | One line: the list version (e.g. `2026-11-06`). Change it whenever you edit the list, or the app won't download the new one. |
| `spamdb.csv` | One number per line: `number,category,negative,positive,neutral,name` |

Lines starting with `#` are ignored. Numbers can have spaces or dashes; the app keeps digits and a leading `+`.

```csv
number,category,negative,positive,neutral,name
+963111234567,telemarketing,12,0,1,Example Co
```

> The current list only has one test entry (`+000000000000`), which isn't a real number.

---

## بالعربي

هي لستة أرقام السبام لتطبيق **[block-number-android](https://github.com/tareknahas85-star/block-number-android)**. التطبيق بينزّلها مرة كل يوم، وبعدها بيشتغل بلا نت.

- `version.txt`: سطر واحد فيه رقم النسخة (متل `2026-11-06`). غيّرو كل ما تعدّل اللستة، وإلا التطبيق ما بينزّل الجديدة.
- `spamdb.csv`: كل سطر رقم: `number,category,negative,positive,neutral,name`
- السطور اللي بتبلّش بـ`#` بيتجاهلها التطبيق.

> هلأ اللستة فيها رقم تجربة واحد بس (`+000000000000`)، ومو رقم حقيقي.