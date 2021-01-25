# LINE QR LOGIN
Generate Line's Cert/AuthToken by QR Code 

Installation
------------
```bash
$ pip3 install lesting.api.client
```

Example
------------
```python
from login import QRLogin

qr = QRLogin()

result = qr.loginWithQrCode("lite")
print("Access Token: " + result.accessToken)
print("Certificate: " + result.certificate)
```