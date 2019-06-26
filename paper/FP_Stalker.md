FP-Stalker : Tracking Browser Fingerprint Evolutions
===============================================================
Author: Antoine Vastel, Pierre Laperdrix, Walter Rudametkin, Romain Rouvoy
Conference / year : 2018 S&P

summary >
It presents the browser fingerprint could change frequently so that the uniqueness of the fingerprinting is not enough to track users. They emphasis the linkability of the browser fingerprinting. It could link the fingerprint to previous one eventhough the configuration of the browser is changed. They introduce the 'FP-Stalker' which provides the ability of linking with two variants such as rule-based or machine learning. Compared with previous algorithm, 

Method > 
- Input data set : 98,598 fingerprints from 1,905 browser instances
- Tool : AmIunique (they build it) extension + Firefox / Chrome 
- duration : 2 years
- 다른 fingerprinting site와 비교해 볼때 다른점 : unique identifier를 얻어낼 수 있음

citation >
- Beauty and the Beast : Diverting Modern Web Browsers to Build Unique Browser Fingerprints (The authors in this paper conducted in 2016) : Eckersely의 논문을 증명함과 동시에 몇몇의 attribute들은 변했다는 것을 발견함
-Eckersley : use simple heuristic - string comparison (make correct guesses 65% of the time)
- efficient Fingerprinting-Based Android Device Identification With Zero-Permission Identifier : 이 paper가 사용한 방법과 유사한 방법으로 linkability를 제공 but, browser를 이용하지는 x. 38가지의 다른 attribute들을 사용 (ringtone, system package...)하였고 naive Bayes classifier를 사용하여 시간의 변화에 따라서도 fingerpint를 잘 link


related work / reference >
- Beauty and the Beast : Diverting Modern Web Browsers to Build Unique Browser Fingerprints
- FP-Detective : Dusting the Web for Fingerprinting (diversity of tracking techniques)
- The Web Never Forgets
- Cookieless Monster : Exploring the Ecosystem of Web-based Device Fingerprinting - browser extension을 이용해서 user의 정보를 spoof하는 것은 id를 만들어내는 든 정보를 다루는 것이 아니다. 따라서 오히려 user를 distinguishablr하게 할 수 있다. 

- Online Tracking : A 1-million-site Measurement and Analysis
- PriVaricator: Deceiving Fingerprinters with Little White Lies

pros >
------

cons >
------

tags >
------
* track devices over long peroids of time
* Linkability
