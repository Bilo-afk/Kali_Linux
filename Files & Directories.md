# 📘 Kali Linux Basics

## 🟢 Section 2: File & Directory Management

This section explains essential file and directory management commands
in Kali Linux.\
هذا القسم يشرح أوامر إدارة الملفات والمجلدات الأساسية في كالي لينكس.

------------------------------------------------------------------------

# 1️⃣ `mkdir`

Creates a new directory.\
ينشئ مجلدًا جديدًا.

``` bash
mkdir test_folder
```

Create nested directories:

``` bash
mkdir -p folder1/folder2/folder3
```

------------------------------------------------------------------------

# 2️⃣ `rmdir`

Removes an empty directory.\
يحذف مجلدًا فارغًا.

``` bash
rmdir test_folder
```

------------------------------------------------------------------------

# 3️⃣ `rm`

Removes files or directories.\
يحذف الملفات أو المجلدات.

``` bash
rm file.txt
```

Remove directory recursively:

``` bash
rm -rf folder_name
```

⚠ Use carefully --- this cannot be undone.

------------------------------------------------------------------------

# 4️⃣ `cp`

Copies files or directories.\
ينسخ الملفات أو المجلدات.

``` bash
cp file.txt backup.txt
```

Copy directory:

``` bash
cp -r folder1 folder2
```

------------------------------------------------------------------------

# 5️⃣ `mv`

Moves or renames files.\
ينقل الملفات أو يغير اسمها.

``` bash
mv file.txt /home/kali/Desktop/
```

Rename file:

``` bash
mv oldname.txt newname.txt
```

------------------------------------------------------------------------

# 6️⃣ `touch`

Creates an empty file.\
ينشئ ملفًا فارغًا.

``` bash
touch newfile.txt
```

------------------------------------------------------------------------

# 7️⃣ `file`

Shows file type.\
يعرض نوع الملف.

``` bash
file newfile.txt
```

------------------------------------------------------------------------

# 8️⃣ `stat`

Displays detailed file information.\
يعرض معلومات تفصيلية عن الملف.

``` bash
stat newfile.txt
```

------------------------------------------------------------------------

# 9️⃣ `tree`

Displays directory structure in tree format.\
يعرض بنية المجلدات بشكل شجري.

``` bash
tree
```

------------------------------------------------------------------------

# 🔟 `locate`

Searches for files quickly (database-based).\
يبحث عن الملفات بسرعة باستخدام قاعدة بيانات.

``` bash
locate file.txt
```

Update database:

``` bash
updatedb
```

------------------------------------------------------------------------

# 1️⃣1️⃣ `find`

Searches files in real-time within directories.\
يبحث عن الملفات داخل المجلدات بشكل مباشر.

``` bash
find /home -name file.txt
```

------------------------------------------------------------------------

# 1️⃣2️⃣ `which`

Shows path of a command.\
يعرض مسار الأمر.

``` bash
which python3
```

------------------------------------------------------------------------

# 1️⃣3️⃣ `whereis`

Locates binary, source, and manual files.\
يحدد موقع الملفات التنفيذية والمصدرية ودليل الاستخدام.

``` bash
whereis bash
```

------------------------------------------------------------------------

# 1️⃣4️⃣ `basename`

Extracts filename from path.\
يستخرج اسم الملف من المسار.

``` bash
basename /home/kali/file.txt
```

------------------------------------------------------------------------

# 1️⃣5️⃣ `dirname`

Extracts directory path from full path.\
يستخرج مسار المجلد من المسار الكامل.

``` bash
dirname /home/kali/file.txt
```

------------------------------------------------------------------------

# 1️⃣6️⃣ `readlink`

Shows the target of a symbolic link.\
يعرض المسار الحقيقي للرابط الرمزي.

``` bash
readlink symlink_name
```

------------------------------------------------------------------------

# 🧠 Section Summary

You learned how to create, delete, copy, move, search, and inspect files
and directories.\
تعلمت كيفية إنشاء، حذف، نسخ، نقل، البحث وفحص الملفات والمجلدات.
