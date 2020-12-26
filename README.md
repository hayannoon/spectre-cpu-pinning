# spectre-cpu-pinning
-------------
### add barrier : isb, dsb를 이용해서 스펙터 방어
### cpuPinning_bigCore : cpu pinning해주는 systemcall을 이용해서 big core로 돌림(vulnerable)
### cpuPinning_littleCore : cpu pinning해주는 system call을 이용해서 little core로 돌림(secure)
### original spectre : 참고했던 spectre 코드 원본(출처 : https://github.com/V-E-O/PoC/tree/master/CVE-2017-5753)
