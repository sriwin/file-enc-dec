# Open SSL - Encryption & Decryption

## Encryption Command
- Note : xyz is the password

```shell
openssl enc -aes-256-cbc -salt -in dec-file.dat -out enc-file.enc -md md5 -k "xyz" -md md5
```

## Decryption Command
- Note : xyz is the password

```shell
openssl enc -d -aes-256-cbc -in enc-file.enc -out dec-file.dec -k "xyz" -md md5

```

