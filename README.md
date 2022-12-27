# کتاب زبان برنامه‌نویسی Rust (ترجمه فارسی)
این پروژه اولین ترجمه من و دوست عزیزم، شایان هستش، طبیعتا مثل هر چیزی خالی از اشکال نیست، امید‌ داریم این پروژه مفید واقع بشه.

میتونید نسخه زبان اصلی این کتاب رو از این [آدرس](https://doc.rust-lang.org/book/) بخونید.

## پیشنیاز
برای ساخت و مطالعه کتاب به شکل محلی، باید mdBook رو از این [آدرس](https://github.com/rust-lang/mdBook/releases) نصب کنید، یا از دستور زیر برای نصب از طریق Cargo استفاده کنید.

```bash
$ cargo install mdbook
```

## ساخت کتاب
این مخزن رو کلون کنید، وارد پوشه پروژه بشید و کتاب رو بسازید.

```bash
$ git clone 'https://github.com/sorensha/rust-book-farsi.git'
$ cd rust-book-farsi
$ mdbook build
```

خروجی در پوشه book قرار میگیره، برای مطالعه و بررسی، فایل index.html موجود در پوشه book رو در مرورگر باز کنید.

_Firefox:_
```bash
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_
```bash
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```
