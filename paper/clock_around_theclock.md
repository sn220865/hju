Clock Around the Clock : Time-Based Device Fingerprinting
=========================================================
author : Iskander Sanchez-Rola, Igor Santos, Davide Balzarotti
<br>conference / year : CCS 2018

summary>
--------
* Purpose : New attributes of fingerprinting
* Hardware-level fingerprinting > Time-based fingerprinting
* source : computer internal clock
* How to : record the timing caused when the instruction in API is executed
* Advantage : do not depend on environment / stable / be good at homogeneous scenario
*Limitation : protection is difficult

pros>
-----
* 다양한 fingerprint assessment metrics를 제시 -> 특히 homogeneous environment를 고려한 것이 매우 흥미로운 접근<br> 
&nbsp;- 일반적인 user 뿐만 아니라 비슷한 디바이스 환경을 공유하는 회사 컴퓨터등을 fingerprint 하는 능력을 평가하기에 좋은 지표<br>
&nbsp;- fingerprint 할 수 있는 user의 pool 다양해짐

* Time-based fingerprinting은 특정 함수나 환경에 의존적이지 않음<br>
&nbsp;- robustness factor로 사용가능

cons>
-----
* 각 방법의 metrics비교는 원 저자의 테스트 결과나 디자인에 기반한 것이므로 실제로 그 metrics가 성립할 가능성도 있다.<br> 
&nbsp;- 예시 : attributed FP에서 일부 attribute는 robustness를 측정하기도 했다. 

* Combination에 webgl과 canvas만 합친 방법에 대한 자료도 있었으면 좋았을 것 깉다.


tag>
----
- analysis of client-side attribute diversity<br>
- hardware-level fingerprinting
- Desktop 
