# Jarkom-Modul-3-IT38-2024

## Anggota Kelompok
### Rafael Gunawan (5027231019)
### Randist Prawanda Putra (5027231059)
<hr>

## Topologi
![image](https://github.com/user-attachments/assets/c959cdb4-3e00-4c80-8cb2-3297fb248e11)

## Konfigurasi Awal
### Paradis
    auto eth0
    iface eth0 inet dhcp
    
    auto eth1
    iface eth1 inet static
    	address 10.82.1.1
    	netmask 255.255.255.0
    
    auto eth2
    iface eth2 inet static
    	address 10.82.2.1
    	netmask 255.255.255.0
    
    auto eth3
    iface eth3 inet static
    	address 10.82.3.1
    	netmask 255.255.255.0
    
    auto eth4
    iface eth4 inet static
    	address 10.82.4.1
    	netmask 255.255.255.0
### Annie
    auto eth0
    iface eth0 inet static
    	address 10.82.1.2
    	netmask 255.255.255.0
    	gateway 10.82.1.1
### Berthold
    auto eth0
    iface eth0 inet static
    	address 10.82.1.3
    	netmask 255.255.255.0
    	gateway 10.82.1.1
### Reiner
    auto eth0
    iface eth0 inet static
    	address 10.82.1.4
    	netmask 255.255.255.0
    	gateway 10.82.1.1
### Armin
    auto eth0
    iface eth0 inet static
    	address 10.82.2.2
    	netmask 255.255.255.0
    	gateway 10.82.2.1
### Eren
    auto eth0
    iface eth0 inet static
    	address 10.82.2.3
    	netmask 255.255.255.0
    	gateway 10.82.2.1
### Mikasa
    auto eth0
    iface eth0 inet static
    	address 10.82.2.4
    	netmask 255.255.255.0
    	gateway 10.82.2.1
### Beast
    auto eth0
    iface eth0 inet static
    	address 10.82.3.2
    	netmask 255.255.255.0
    	gateway 10.82.3.1
### Colossal
    auto eth0
    iface eth0 inet static
    	address 10.82.3.3
    	netmask 255.255.255.0
    	gateway 10.82.3.1
### Warhammer
    auto eth0
    iface eth0 inet static
    	address 10.82.3.4
    	netmask 255.255.255.0
    	gateway 10.82.3.1
### Fritz
    auto eth0
    iface eth0 inet static
    	address 10.82.4.2
    	netmask 255.255.255.0
    	gateway 10.82.4.1
### Tybur
    auto eth0
    iface eth0 inet static
    	address 10.82.4.3
    	netmask 255.255.255.0
    	gateway 10.82.4.1
### Zeke dan Erwin
    auto eth0
    iface eth0 inet dhcp
