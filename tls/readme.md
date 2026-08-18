To enable HTTPS

- put your `cert.pem` and `key.pem` files in this folder (tls)
- uncomment `- ./tls:/tls` in the `compose.yml` volumes section 
- and uncomment `tls-cert` and `tls-key` options in the `config.yml`