## Os-based
* Kali linux
* Debian testing
* ...

## Softwares
1. [Mendely](www.mendeley.com/)
2. [wkhtmltopdf](https://wkhtmltopdf.org/)
3. ...

## Errors detail
```
QSslSocket: cannot resolve CRYPTO_num_locks
QSslSocket: cannot resolve CRYPTO_set_id_callback
QSslSocket: cannot resolve CRYPTO_set_locking_callback
QSslSocket: cannot resolve ERR_free_strings
QSslSocket: cannot resolve sk_new_null
QSslSocket: cannot resolve sk_push
QSslSocket: cannot resolve sk_free
QSslSocket: cannot resolve sk_num
QSslSocket: cannot resolve sk_pop_free
QSslSocket: cannot resolve sk_value
QSslSocket: cannot resolve SSL_library_init
QSslSocket: cannot resolve SSL_load_error_strings
QSslSocket: cannot resolve SSL_get_ex_new_index
QSslSocket: cannot resolve SSLv2_client_method
QSslSocket: cannot resolve SSLv3_client_method
QSslSocket: cannot resolve SSLv23_client_method
QSslSocket: cannot resolve SSLv2_server_method
QSslSocket: cannot resolve SSLv3_server_method
QSslSocket: cannot resolve SSLv23_server_method
QSslSocket: cannot resolve X509_STORE_CTX_get_chain
QSslSocket: cannot resolve OPENSSL_add_all_algorithms_noconf
QSslSocket: cannot resolve OPENSSL_add_all_algorithms_conf
QSslSocket: cannot resolve SSLeay
QSslSocket: cannot resolve SSLeay_version
QSslSocket: cannot call unresolved function SSLeay
QSslSocket: cannot call unresolved function CRYPTO_num_locks
QSslSocket: cannot call unresolved function CRYPTO_set_id_callback
QSslSocket: cannot call unresolved function CRYPTO_set_locking_callback
QSslSocket: cannot call unresolved function SSL_library_init
QSslSocket: cannot call unresolved function SSLv23_client_method
QSslSocket: cannot call unresolved function sk_num
```


## Resove Method

```
apt install openssl libssl-dev libssl1.0.2 libssl1.0-dev
```

## Key

> The problem is the last two dependances: **libssl1.0.2** , **libssl1.0-dev**
