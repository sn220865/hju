A Privacy Analysis of Cross-device Tracking
===========================================
Author : Sebastian Zimmeck, Jie S. Li and Hyungtae Kim, Steven M. Bellovin and Tony Jebara
Conference / year : USENIX 2017

summary >
---------
* Purpose: adoption on the web server-side, cross-device tracking
* Source : IP address, domain URL
* How to : collect ip address and domain URL, and calculate the similarity and match the device
* Advantage : own dataset, can cross-device fingerprinting
* Limitation : dataset is homogeneous, could not compare our approach to other real dataset

pros>
-----
* CDT 직접 collect한 것이 매우 좋은 시도이고, 이를 위해 project용 web site와 browser extension, android app을 직접 구현한 것이 흥미로움

* Domain url이 IP address의 한계를 보완해준다는 사실 증명

cons>
-----
* 다양한 fingerprinting factor 들이 있는데 그 것들을 더 적용해보고 비교해 보면 좋을 것 같다.

tags>
-----
* Advanced solutions to collect additional fingerprintable attributes
* IP+domain URL
* Analysis of fingerprinting adoption on the web and server-side scripts
* machine learning 
* cross device tracking
