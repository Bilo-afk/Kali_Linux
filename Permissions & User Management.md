# 📘 Kali Linux Basics

## 🟢 Section 4: Permissions & User Management

This section explains essential commands used to manage permissions,
users, and groups in Kali Linux.\
هذا القسم يشرح أوامر إدارة الصلاحيات والمستخدمين والمجموعات في كالي
لينكس.

------------------------------------------------------------------------

# 1️⃣ `chmod`

Changes file permissions.\
يغير صلاحيات الملف.

``` bash
chmod 755 script.sh
```

Symbolic mode example:

``` bash
chmod +x script.sh
```

------------------------------------------------------------------------

# 2️⃣ `chown`

Changes file owner.\
يغير مالك الملف.

``` bash
chown kali file.txt
```

Change owner and group:

``` bash
chown kali:kali file.txt
```

------------------------------------------------------------------------

# 3️⃣ `chgrp`

Changes group ownership.\
يغير مجموعة الملف.

``` bash
chgrp developers file.txt
```

------------------------------------------------------------------------

# 4️⃣ `sudo`

Runs command with superuser privileges.\
يشغل الأمر بصلاحيات المدير.

``` bash
sudo apt update
```

------------------------------------------------------------------------

# 5️⃣ `su`

Switches user account.\
يبدل إلى مستخدم آخر.

``` bash
su root
```

------------------------------------------------------------------------

# 6️⃣ `adduser`

Creates a new user.\
ينشئ مستخدمًا جديدًا.

``` bash
sudo adduser newuser
```

------------------------------------------------------------------------

# 7️⃣ `deluser`

Deletes a user.\
يحذف مستخدمًا.

``` bash
sudo deluser newuser
```

------------------------------------------------------------------------

# 8️⃣ `usermod`

Modifies a user account.\
يعدل إعدادات مستخدم.

Add user to group:

``` bash
sudo usermod -aG sudo newuser
```

------------------------------------------------------------------------

# 9️⃣ `groupadd`

Creates a new group.\
ينشئ مجموعة جديدة.

``` bash
sudo groupadd developers
```

------------------------------------------------------------------------

# 🔟 `passwd`

Changes user password.\
يغير كلمة مرور المستخدم.

``` bash
passwd
```

Change another user's password:

``` bash
sudo passwd newuser
```

------------------------------------------------------------------------

# 🧠 Section Summary

You learned how to manage file permissions, switch users, create
accounts, and control access.\
تعلمت كيفية إدارة الصلاحيات، تبديل المستخدمين، إنشاء الحسابات والتحكم
بالوصول.
