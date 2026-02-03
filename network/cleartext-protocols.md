\# Cleartext protocols 



\# What are cleartext protocols 

Cleartext protocols are network protocols that transfer data without encryption meaning they are vulnerable to being attacked and an attacker gaining their information. 



\# What protocols are cleartext 

* HTTP (html document transfer)
* Telnet (remote access) 
* FTP (files) 
* SMTP (email)



\# MITM

With MITM (man-in-the-middle) attacks, attackers can secretly intercept the data and communication of your device, potentially leaking sensitive data like login credentials, bank account information, or tokens. 

Wireshark can be used to detect packet transfer from the victim and analyze packet data metadata. 



\# Mitigation

* Generally, avoid old / cleartext protocols 
* Use encryption such as AES (symmetric encryption algorithm) or RSA (asymmetric) 
* Use strong passwords with MFA
* Avoid using untrusted, public Wi-Fi networks with no security 



