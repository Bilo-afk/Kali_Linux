# 📘 Kali Linux Basics

## 🟢 Section 3: File Viewing & Reading Commands

This section explains essential commands used to view and analyze file
contents in Kali Linux.\
هذا القسم يشرح الأوامر المستخدمة لعرض وقراءة وتحليل محتوى الملفات في
كالي لينكس.

------------------------------------------------------------------------

# 1️⃣ `cat`

Displays the full content of a file.\
يعرض محتوى الملف بالكامل.

``` bash
cat file.txt
```

Combine files:

``` bash
cat file1.txt file2.txt
```

------------------------------------------------------------------------

# 2️⃣ `tac`

Displays file content in reverse order.\
يعرض محتوى الملف بالعكس (من الأسفل للأعلى).

``` bash
tac file.txt
```

------------------------------------------------------------------------

# 3️⃣ `less`

Views file content page by page (recommended for large files).\
يعرض الملف صفحة بصفحة (مفيد للملفات الكبيرة).

``` bash
less file.txt
```

Exit with:

``` bash
q
```

------------------------------------------------------------------------

# 4️⃣ `more`

Simple pager for viewing file content.\
يعرض الملف صفحة بصفحة بطريقة أبسط.

``` bash
more file.txt
```

------------------------------------------------------------------------

# 5️⃣ `head`

Displays the first 10 lines of a file by default.\
يعرض أول 10 أسطر من الملف.

``` bash
head file.txt
```

Specify number of lines:

``` bash
head -n 20 file.txt
```

------------------------------------------------------------------------

# 6️⃣ `tail`

Displays the last 10 lines of a file by default.\
يعرض آخر 10 أسطر من الملف.

``` bash
tail file.txt
```

Specify number of lines:

``` bash
tail -n 20 file.txt
```

------------------------------------------------------------------------

# 7️⃣ `tail -f`

Monitors file changes in real time (useful for logs).\
يراقب تغييرات الملف مباشرة (مفيد لملفات السجل).

``` bash
tail -f /var/log/syslog
```

Stop with:

``` bash
Ctrl + C
```

------------------------------------------------------------------------

# 8️⃣ `nl`

Displays file content with line numbers.\
يعرض محتوى الملف مع ترقيم الأسطر.

``` bash
nl file.txt
```

------------------------------------------------------------------------

# 9️⃣ `wc`

Counts lines, words, and characters in a file.\
يحسب عدد الأسطر والكلمات والأحرف.

``` bash
wc file.txt
```

Count lines only:

``` bash
wc -l file.txt
```

------------------------------------------------------------------------

# 🔟 `strings`

Extracts readable text from binary files.\
يستخرج النصوص المقروءة من الملفات الثنائية.

``` bash
strings program.exe
```

------------------------------------------------------------------------

# 🧠 Section Summary

You learned how to display, monitor, and analyze file contents
efficiently.\
تعلمت كيفية عرض ومراقبة وتحليل محتوى الملفات باحتراف.
