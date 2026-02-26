# 📘 Kali Linux Basics

## 🟢 Section 5: Package Management (APT & DPKG)

This section explains essential commands used to manage software
packages in Kali Linux.\
هذا القسم يشرح أوامر إدارة الحزم والبرامج في كالي لينكس.

------------------------------------------------------------------------

# 1️⃣ `apt update`

Updates the package list from repositories.\
يقوم بتحديث قائمة الحزم من المستودعات.

``` bash
sudo apt update
```

------------------------------------------------------------------------

# 2️⃣ `apt upgrade`

Upgrades installed packages to the latest version.\
يقوم بتحديث البرامج المثبتة إلى أحدث إصدار.

``` bash
sudo apt upgrade
```

------------------------------------------------------------------------

# 3️⃣ `apt install`

Installs a new package.\
يثبت برنامجًا جديدًا.

``` bash
sudo apt install nmap
```

------------------------------------------------------------------------

# 4️⃣ `apt remove`

Removes an installed package (keeps configuration files).\
يحذف البرنامج مع الإبقاء على ملفات الإعداد.

``` bash
sudo apt remove nmap
```

------------------------------------------------------------------------

# 5️⃣ `apt purge`

Removes a package including configuration files.\
يحذف البرنامج مع ملفات الإعداد بالكامل.

``` bash
sudo apt purge nmap
```

------------------------------------------------------------------------

# 6️⃣ `apt autoremove`

Removes unused dependencies.\
يحذف الحزم غير المستخدمة تلقائيًا.

``` bash
sudo apt autoremove
```

------------------------------------------------------------------------

# 7️⃣ `apt search`

Searches for a package in repositories.\
يبحث عن برنامج داخل المستودعات.

``` bash
apt search wireshark
```

------------------------------------------------------------------------

# 8️⃣ `apt show`

Displays detailed information about a package.\
يعرض معلومات تفصيلية عن البرنامج.

``` bash
apt show nmap
```

------------------------------------------------------------------------

# 9️⃣ `dpkg -i`

Installs a local .deb package file.\
يثبت ملف حزمة بصيغة .deb من الجهاز.

``` bash
sudo dpkg -i package.deb
```

------------------------------------------------------------------------

# 🔟 `dpkg -l`

Lists installed packages.\
يعرض قائمة البرامج المثبتة.

``` bash
dpkg -l
```

------------------------------------------------------------------------

# 🧠 Section Summary

You learned how to update, install, remove, and manage software packages
in Kali Linux.\
تعلمت كيفية تحديث، تثبيت، حذف وإدارة البرامج في كالي لينكس.
