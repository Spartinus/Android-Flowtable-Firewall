# Android Flowtable Firewall

Android Flowtable Firewall (short: AFF) is the next generation firewall for Android. 


# Benefits over AFWall+ (iptables)

iptables are slow and do not utilizing your hardware, which means everything runs in software. [Flowtables](https://wiki.nftables.org/wiki-nftables/index.php/Flowtable) forwarding packages in software or if supported native via hardware, which depends if your NIC supports it or not. 

* Better performance compared to ntftables or iptables
* Compatibility 
* Hardware support for modern NIC's
* Full Android support
* Works via GUI (Terminal/Termux) or via GUI


# Kernel

You need a Linux 5.5+ kernel (_27. Jan or 3. Febr. 2020_).
