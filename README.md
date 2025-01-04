# Netwerk-Documentatie

1 basis config van de switch

line console 0
password ConsoleWachtwoord123
login
exit

1 basis config van de router

interface GigabitEthernet0/0/0
ip address 192.168.1.1 255.255.255.128
ipv6 address 2001:db8:1::1/65
no shutdown
exit
