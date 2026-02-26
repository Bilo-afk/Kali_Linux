# 📘 Kali Linux Basics

## 🟢 Section 6: Networking Commands

This section explains essential networking commands used in Kali Linux
for monitoring, troubleshooting, and basic network analysis.\
هذا القسم يشرح أوامر الشبكات الأساسية المستخدمة في كالي لينكس للمراقبة
والتحليل وحل المشاكل.

------------------------------------------------------------------------

# 1️⃣ `ifconfig`

Displays or configures network interfaces (older tool).\
يعرض أو يضبط إعدادات كروت الشبكة (أداة قديمة).

``` bash
ifconfig
```

------------------------------------------------------------------------

# 2️⃣ `ip a`

Displays IP address information (modern replacement for ifconfig).\
يعرض معلومات عناوين IP (الأداة الحديثة).

``` bash
ip a
```

------------------------------------------------------------------------

# 3️⃣ `ip route`

Shows routing table.\
يعرض جدول التوجيه.

``` bash
ip route
```

------------------------------------------------------------------------

# 4️⃣ `ping`

Tests connectivity between your machine and another host.\
يختبر الاتصال بين جهازك وجهاز آخر.

``` bash
ping google.com
```

------------------------------------------------------------------------

# 5️⃣ `netstat`

Displays network connections and listening ports.\
يعرض الاتصالات الحالية والمنافذ المفتوحة.

``` bash
netstat -tuln
```

------------------------------------------------------------------------

# 6️⃣ `ss`

Modern alternative to netstat.\
بديل حديث لأمر netstat.

``` bash
ss -tuln
```

------------------------------------------------------------------------

# 7️⃣ `route`

Displays or modifies routing table (older command).\
يعرض أو يعدل جدول التوجيه (أمر قديم).

``` bash
route -n
```

------------------------------------------------------------------------

# 8️⃣ `arp`

Displays or modifies ARP table.\
يعرض جدول ARP.

``` bash
arp -a
```

------------------------------------------------------------------------

# 9️⃣ `traceroute`

Shows the path packets take to reach a destination.\
يعرض المسار الذي تسلكه الحزم للوصول إلى الهدف.

``` bash
traceroute google.com
```

------------------------------------------------------------------------

# 🔟 `nslookup`

Queries DNS to obtain domain information.\
يستعلم عن معلومات DNS لنطاق معين.

``` bash
nslookup google.com
```

------------------------------------------------------------------------

# 1️⃣1️⃣ `dig`

Advanced DNS lookup tool.\
أداة متقدمة للاستعلام عن DNS.

``` bash
dig google.com
```

------------------------------------------------------------------------

# 1️⃣2️⃣ `whois`

Retrieves domain registration information.\
يعرض معلومات تسجيل النطاق.

``` bash
whois google.com
```

------------------------------------------------------------------------

# 1️⃣3️⃣ `macchanger`

Changes MAC address of a network interface.\
يغير عنوان MAC لكرت الشبكة.

``` bash
sudo macchanger -r eth0
```

------------------------------------------------------------------------

# 1️⃣4️⃣ `iwconfig`

Displays wireless interface information.\
يعرض معلومات كرت الشبكة اللاسلكية.

``` bash
iwconfig
```

------------------------------------------------------------------------

# 1️⃣5️⃣ `airmon-ng`

Enables monitor mode on wireless interfaces (used in security testing).\
يفعل وضع المراقبة لكرت الواي فاي (يستخدم في الاختبارات الأمنية).

``` bash
sudo airmon-ng start wlan0
```

------------------------------------------------------------------------

# 🧠 Section Summary

You learned how to check connectivity, analyze routes, inspect ports,
query DNS, and manage network interfaces.\
تعلمت كيفية فحص الاتصال، تحليل المسارات، عرض المنافذ، الاستعلام عن DNS
وإدارة كروت الشبكة.
