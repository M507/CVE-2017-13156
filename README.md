### Check-CVE-2017-13156.py


```sh
root@ubuntu:~/CVE-2017-13156$ pip install androguard
root@ubuntu:~/CVE-2017-13156$ python Check-CVE-2017-13156.py InsecureBankv2.apk

Checking if InsecureBankv2.apk is vulnerable to CVE-2017-13156 vulnerability

InsecureBankv2.apk md5: 5ee4829065640f9c936ac861d1650ffc

InsecureBankv2.apk is signed
v1 scheme: True
v2 scheme: False
v3 scheme: False
minSdkVersion: 15 
InsecureBankv2.apk 5ee4829065640f9c936ac861d1650ffc is VULNERABLE
InsecureBankv2.apk can be exploited on devices running Android version < 8.0.0
```