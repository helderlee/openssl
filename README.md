# OpenSSL

### RSA keys:

openssl genrsa -aes256 -out private.pem 4096

### Extract RSA public key from private key:

openssl rsa -in private.pem -outform PEM -pubout -out public.pem
