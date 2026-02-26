# 📘 Kali Linux Basics

## 🟢 Final Section: Compression & Archiving Commands

This section explains essential commands used for compressing and
extracting files in Kali Linux.\
هذا القسم يشرح أوامر ضغط وفك ضغط الملفات في كالي لينكس.

------------------------------------------------------------------------

# 1️⃣ `tar`

Creates an archive file.\
ينشئ ملف أرشيف.

``` bash
tar -cvf archive.tar folder_name
```

-   c → create\
-   v → verbose\
-   f → file

------------------------------------------------------------------------

# 2️⃣ `tar -xvf`

Extracts an archive file.\
يفك ضغط ملف أرشيف.

``` bash
tar -xvf archive.tar
```

Extract compressed archive:

``` bash
tar -xvzf archive.tar.gz
```

------------------------------------------------------------------------

# 3️⃣ `zip`

Compresses files into .zip format.\
يضغط الملفات بصيغة zip.

``` bash
zip archive.zip file.txt
```

Compress folder:

``` bash
zip -r archive.zip folder_name
```

------------------------------------------------------------------------

# 4️⃣ `unzip`

Extracts .zip files.\
يفك ضغط ملفات zip.

``` bash
unzip archive.zip
```

------------------------------------------------------------------------

# 5️⃣ `gzip`

Compresses a file using gzip.\
يضغط ملف باستخدام gzip.

``` bash
gzip file.txt
```

Decompress:

``` bash
gunzip file.txt.gz
```

------------------------------------------------------------------------

# 🧠 Section Summary

You learned how to create archives, compress files, and extract
different archive formats.\
تعلمت كيفية إنشاء الأرشيفات، ضغط الملفات، وفك ضغطها بصيغ مختلفة.
