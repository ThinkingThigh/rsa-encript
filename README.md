# rsa-encript

rsa-encript 

# Usage
## Install

```
npm i rsa-encript
```


```
import { RSAKey } from "rsa-encript";

//...
    let pwd = "123456"
    let rsa = new RSAKey();
    let modulus = process.env.VUE_APP_MODULUS;
    let exponent = "10001";
    rsa.setPublic(modulus, exponent);
    let encrypted_pwd = rsa.encrypt(pwd));
//...
```